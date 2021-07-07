
# Why do we use parameters?
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, 

```
parameters:
  applicationId:
    in: header
    name: X-Application-Id
    required: true
    type: string
    description: 'Id of the Application that is using the API.'
  userId: 
    in: header
    name: X-User-Id
    required: true
    type: string
    description: 'Id of the User that is using the API.'
  traceId:
    in: header
    name: X-Trace-Id
    required: true
    type: string
    description: 'Trace ID that is using the API.'
  companyId: 
    in: query
    name: companyId
    required: true
    type: string
    description: 'Id of the Company that is using the API.'
  entity:
    in: body
    name: entity
    required: true
    description: 'description about entity'
    schema:
      $ref: '#/definitions/Entity' 

```

There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.

```
paths:
  /entity:
    get:
      tags:
        - business domain
      summary: entity
      description: 'entity'

```

