Skinned model pipeline.
Generate the code with visual studio, and import the dll in with mgcb, in references.
You should have a new Pipeline available to load your Model.
If the generation failed, and you don't see any error in the object processor, launch the mgcb process in command line (use the same command specified in Visual studio output/errors). 
You should already see more information on the error, for example lack of armature, missing skinning data (relation between the skeleton and the mesh).
