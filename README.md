Provides an implementation of Archimate 3.0 modeling language for MetaEdit+ (www.metacase.com/download).

- .mec file includes the metamodel and example models, following ArchiMate version 3.0.1
- .mxs file includes library symbols

After importing these two files into MetaEdit+ you may apply Archimate. For importining choose Repository | Import... (https://www.metacase.com/support/55/manuals/meplus/Mp-5_3_2.html) The main objective for this implemenation is being able to integrate Archimate with other modeling languages, like BPMN related to processes, Class diagrams related to data objects and elements of Archimate etc. Integrated models provide then richer specification, removes the need to maintain different models (e.g. rename processes in both BPMN and ArchiMate, or Class name in UML and data object in Archimate. Also the consistency of the specifications can be then better ensured. Additionally, reporting over integrated models, metrics, documentation, code generation etc. become possible. Metamodel extensions can be done with MetaEdit+ Workbench.

Note that ArchiMate 3.0 standard has tens, if not hundreds, of errors as also acknowledged by Archimate consortium. The currently implemented 3.0.1 version is expected to be correct these but since the specification is still made manually by the consortium as in the past omissions are errors are likely. This should be acknowledge when using ArchiMate, including the implementation provided here. With MetaEdit+ you may, however, correct the metamodel (and notation and checks) while you are using it, extend ArchiMate metamodel, or take parts of it to fit with your specification of enterprise architecture.

*The ArchiMate standard is a copyright of The Open Group and ArchiMate is a registered trademark of The Open Group. The use of
ArchiMate in this product has not been certified by The Open Group and no endorsement or warranty, expressed or implied, is granted for its use.
