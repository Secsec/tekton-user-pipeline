To use the pipeline, you just have to create a PipelineRun (pipelinerun-create-user.yml) with the proper parameters to launch the pipeline.
Dont forget to create the secret and the rolebinding (allowing to create users, namespaces and rolebinding) to the serviceAccount that will be running the Pipeline.
