# python

The below projects are implemented in python as indicated by the bullet points below each project:

- Server-side applications
    + [dpnt-coverage](dpnt-coverage.md)
        * version 2.7
        * inside docker container 
            * see folder [container/images/base](https://github.com/julianghionoiu/dpnt-coverage/tree/master/container/images/base) in project root
            * see folder [container/images/python](https://github.com/julianghionoiu/dpnt-coverage/tree/master/container/images/python) in project root
    + [dpnt-infra-events](dpnt-infra-events.md)
        * submodule(s)
            - [tdl-local-sqs (local-sqs)](https://github.com/julianghionoiu/tdl-local-sqs)
    + [dpnt-sourcecode](dpnt-sourcecode.md)
        * submodules:
            - [tdl-local-ecs (local-ecs)](tdl-local-ecs.md)
            - [tdl-local-s3 (local-s3)](tdl-local-s3.md)
            - [tdl-local-sqs (local-sqs)](tdl-local-sqs.md)    
    + [dpnt-video](dpnt-video.md)
        * version 2.7
        * inside docker container 
            * see folder container/images/base in project root
            * see folder container/images/python in project root
    + [tdl-participant-data-service](tdl-participant-data-service.md)
        + submodules:
            + [tdl-local-ses (local-ses)](tdl-local-ses.md)
            + [tdl-local-sqs (local-sqs)](tdl-local-sqs.md)

- Client-facing applications
    + [tdl-runner-python](tdl-runner-python.md)
        * version 2.7 
        * Dependenc(ies)
            + [tdl-client-python](tdl-client-python.md)
    + [tdl-runner-scala](tdl-runner-scala.md)
    + [tdl-runner-vbnet](tdl-runner-vbnet.md)

- Dependencies shared across client/server applications
    + [tdl-client-test-broker](tdl-client-test-broker.md)
    + [tdl-client-test-wiremock](tdl-client-test-wiremock.md)

- Dependencies used by client/server applications
    + [tdl-client-dotnet](tdl-client-dotnet.md)
    + [tdl-client-java](tdl-client-java.md)
    + [tdl-client-nodejs](tdl-client-nodejs.md)
    + [tdl-client-python](tdl-client-python.md)
    + [tdl-client-ruby](tdl-client-ruby.md)
    + [tdl-client-spec](tdl-client-spec.md)

- Test Stubs as git submodules
    - [tdl-local-ecs](tdl-local-ecs.md)
    - [tdl-local-github](tdl-local-github.md)
    - [tdl-local-s3](tdl-local-s3.md)
    - [tdl-local-ses](tdl-local-ses.md)
    - [tdl-local-sqs](tdl-local-sqs.md)