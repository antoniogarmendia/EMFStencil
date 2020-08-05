__EMF-Stencil__ : is an Eclipse plug-in that facilitates the creation of scalable editing environments for graphical DSLs. 

EMF-Stencil isolate developers from complex technical and implementation details. Given the meta-model with the abstract syntax of a DSL, the tool uses different customizable heuristics to assign graphical representations and styles to the DSL elements, which can be subsequently refined through wizards. 

Starting from this definition, EMF-Stencil produces a Sirius graphical or tabular editor for the DSL.

This tool is integrated with [DSL-tao](http://jdelara.github.io/DSL-tao/index.html), but can also be used stand-alone.

### __Installation__

[Installation Manual of EMF-Stencil](./pages/installation-manual.html)

[Check the list of Dependencies](./pages/list-dependencies.html)

EMF-Stencil is an Eclipse plug-in. Install it by choosing Help → Install New Software….

__Eclipse update site__: [https://antoniogarmendia.github.io/emfsplitter/](https://antoniogarmendia.github.io/emfsplitter/) 

![Select __EMF-Stencil and EMF-Splitter__ and install](/assets/img/eclipse-update-site-emf-stencil.png)

### __Gallery of Graphical DSLs__

To show the capabilities of this tool in building visual languages of different kinds, we create a repository with a set of examples of graphical editors.

[Repository of graphical DSLs](https://github.com/antoniogarmendia/gallery-graphical-dsls-emfStencil)

[This video shows how to import and use the generated CRALA environment](https://youtu.be/rFLJQfhcVyA)

Note: EMF-Stencil must be installed in order to test these generated graphical editors.

### __EMF-Stencil and EMF-Splitter__

The tool integrates [EMF-Splitter](https://antoniogarmendia.github.io/EMFSplitterSite/), which allows defining fragmentation
policies to organize the diagrams of the DSL in different kinds of files and folders. This results in scalable environments where diagrams can be modularly defined by smaller fragments.

[Video Tutorial](https://www.youtube.com/watch?v=tJL7Xfmz3vE)

[Example using the CAEX language meta-model](./pages/caex-example.html)

### Contributors
EMF-Stencil is built by the [miso group](http://www.miso.es) and contributed by: [antoniogarmendia](https://github.com/antoniogarmendia), [estherguerra](https://github.com/estherguerra), [jdelara](https://github.com/jdelara) 
