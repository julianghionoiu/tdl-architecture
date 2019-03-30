# python

The below projects are implemented in python as indicated by the bullet points below each project:

- **Server-side applications**
    + [dpnt-coverage](dpnt-coverage.md)
        - python 2.7 
        - Prod/Dev/Test runtime
        * inside docker container 
            * see folder [container/images/base](https://github.com/julianghionoiu/dpnt-coverage/tree/master/container/images/base) in project root
            * see folder [container/images/[dependent images of base]](https://github.com/julianghionoiu/dpnt-coverage/tree/master/container/images/[dependent images of base]) in project root
            * see folder [container/images/python](https://github.com/julianghionoiu/dpnt-coverage/tree/master/container/images/python) in project root
            * 
    + [dpnt-infra-events](dpnt-infra-events.md)
        - python 3.7 
        - Prod/Dev/Test runtime
        * submodule(s)
            - [tdl-local-sqs (local-sqs)](https://github.com/julianghionoiu/tdl-local-sqs)
    + [dpnt-sourcecode](dpnt-sourcecode.md)
        - python 3.7 
        - Prod/Dev/Test runtime
        * submodules:
            - [tdl-local-ecs (local-ecs)](tdl-local-ecs.md)
            - [tdl-local-s3 (local-s3)](tdl-local-s3.md)
            - [tdl-local-sqs (local-sqs)](tdl-local-sqs.md)    
    + [dpnt-video](dpnt-video.md)
        * version 2.7
        * Prod/Dev/Test runtime
        * inside docker container 
            * see folder container/images/base in project root
    + [tdl-participant-data-service](tdl-participant-data-service.md)
        + python 3.7 
        + Dev/Test runtime
        + submodules:
            + [tdl-local-ses (local-ses)](tdl-local-ses.md)
            + [tdl-local-sqs (local-sqs)](tdl-local-sqs.md)

- **Client-facing applications**
    + Prod/Dev/Test runtime
        * [tdl-runner-python](tdl-runner-python.md)
            - python 3.7 
            - dependenc(ies)
                * [tdl-client-python](tdl-client-python.md)

- **Dependencies shared by client/server applications**
    - Dev/Test runtime
        * [tdl-client-dotnet](tdl-client-dotnet.md)
            + python 3.7 
            - submodules:
                + [tdl-client-test-broker (broker)](tdl-client-test-broker.md)
                + [tdl-client-test-wiremock (wiremock)](tdl-client-test-wiremock.md)
        * [tdl-client-java](tdl-client-java.md)
            + python 3.7 
            - submodules:
                + [tdl-client-test-broker (broker)](tdl-client-test-broker.md)
                + [tdl-client-test-wiremock (wiremock)](tdl-client-test-wiremock.md)
        * [tdl-client-nodejs](tdl-client-nodejs.md)
            + python 3.7 
            - submodules:
                + [tdl-client-test-broker (broker)](tdl-client-test-broker.md)
                + [tdl-client-test-wiremock (wiremock)](tdl-client-test-wiremock.md)
        * [tdl-client-python](tdl-client-python.md)
            + python 3.7 
            - submodules:
                + [tdl-client-test-broker (broker)](tdl-client-test-broker.md)
                + [tdl-client-test-wiremock (wiremock)](tdl-client-test-wiremock.md)
        * [tdl-client-ruby](tdl-client-ruby.md)
            + python 3.7 
            - submodules:
                + [tdl-client-test-broker (broker)](tdl-client-test-broker.md)
                + [tdl-client-test-wiremock (wiremock)](tdl-client-test-wiremock.md)

- **Test Stubs as git submodules**
    - Dev/Test runtimes only
        + [tdl-client-test-broker](tdl-client-test-broker.md)
            * version 3.7
        + [tdl-client-test-wiremock](tdl-client-test-wiremock.md)
            * version 3.7
        - [tdl-local-ecs](tdl-local-ecs.md)
            * version 3.7
        - [tdl-local-github](tdl-local-github.md)
            * version 3.7
        - [tdl-local-s3](tdl-local-s3.md)
            * version 3.7
        - [tdl-local-ses](tdl-local-ses.md)
            * version 3.7
        - [tdl-local-sqs](tdl-local-sqs.md)
            * version 3.7