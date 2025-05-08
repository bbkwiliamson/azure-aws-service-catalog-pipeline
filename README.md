# azure-aws-service-catalog-pipeline

this is a simple pipeline that triggers service catalog product to deploy aws service/product or infrastructure needed.
the source code sits on azure account (repos. devops, pipelines) while deployed infra is on aws account

azure pipelines executes everything based on the file azure-pipelines.yml, this file must always be on the root of the repo.
