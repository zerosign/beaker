scalapb_library(
    name='protobuf',
    sources=rglobs('*.proto'),
    flat_package=True,
    dependencies=[
        '3rdparty/jvm:scalapb-runtime',
        '3rdparty/jvm:scalapb-runtime-grpc',
    ],
    provides=artifact(
        org='com.madavan',
        name='beaker-protobuf',
        repo=public,
        publication_metadata=describe,
    ),
)