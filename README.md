An implementation of Archimate 3.1 modeling language for MetaEdit+ (www.metacase.com/download) for collaborative modeling, model checking, publishing and model exchange. 

- .mec file includes the metamodel and example models following ArchiMate version 3.1
  - includes support for exporting the models in ArchiMate model exchange format
  - includes support for importing ArchiMate model with diagram representation
  - covers derivation rules for valid relationships as shown optionally in diagram or via separate reports
- .mxs file includes library symbols

After importing these two files into MetaEdit+ you may apply Archimate. For importing choose Repository | Import... (https://www.metacase.com/support/55/manuals/meplus/Mp-5_3_2.html) The main objective for this implementation is being able to integrate Archimate with other modeling languages, like BPMN related to processes, Class diagrams related to data objects and elements of Archimate etc. Integrated models provide then richer specification, removes the need to maintain different models (e.g. rename processes in both BPMN and ArchiMate, or Class name in UML and Data object in Archimate). Also the consistency of the specifications can then be better ensured. Additionally, reporting over integrated models, metrics, documentation, code generation etc. becomes possible. Metamodel extensions can be done with MetaEdit+ Workbench.

Note that releases of ArchiMate 2.0 and 3.0 have had tens, if not hundreds, of errors as also been acknowledged by Archimate consortium. The currently implemented 3.1 version is expected to correct these but since the specification is still made manually by the consortium omissions and errors are likely. This should be acknowledge when using ArchiMate, including the implementation provided here. With MetaEdit+ you may, however, correct the metamodel (and notation, checks, model export) while you are using it, extend ArchiMate metamodel, or take parts of it to fit with your specification of enterprise architecture.

"The ArchiMate standard is a copyright of The Open Group and ArchiMate is a registered trademark of The Open Group. The use of
ArchiMate in this product has not been certified by The Open Group and no endorsement or warranty, expressed or implied, is granted for its use."
