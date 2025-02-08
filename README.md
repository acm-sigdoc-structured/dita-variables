# Sample sources for the ACM SIGDOC article of DITA variables.
These source maps and topics are used as exaples in the ACM SIGDOC Structured Authoring article on using DITA variables. The following three DITA rootmaps illustrate different aspects of using DITA variables.   

* ``rootmap_dita-variables.ditamap``: This map illustrates how DITA supports basic variable definition and referencing. This map references one DITA topic, ``advertisement-print.dita``. That topic contains three content references (@conrefs) to variables defined in the library topic ``library-basic.dita``.  

* ``rootmap_everlast.ditamap``: This map illustrates how to define and reference variables using DITA keys. This map references one key library, ``keymap_everlast.ditamap``, and one content topic, ``intro.dita``. This topic contains one key-based reference to a key defined in ``keymap_everlast.ditamap``.   

* ``rootmap_maxview.ditamap``: Similar to ``rootmap_everlast.ditamap``, this map references one key definition library, ``keymap_maxview.ditamap``, and one content topic, ``intro.dita``. This topic is identical for both root maps and illustrates how a topic can inherit key values from different key definition maps.
