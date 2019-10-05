Source: 3fd  
Version: 2.6.2-3  
Description: C++ Framework For Fast Development  
Build-Depends: boost-lockfree (windows), boost-regex (windows), poco (windows), sqlite3, rapidxml  
control: vcpkg/ports/3fd/CONTROL

Source: 7zip  
Version: 19.00  
Description: Library for archiving file with a high compression ratio.  
control: vcpkg/ports/7zip/CONTROL

Source: abseil  
Version: 2019-05-08-1  
Homepage: https://github.com/abseil/abseil-cpp  
Description: an open-source collection designed to augment the C++ standard library.  
  Abseil is an open-source collection of C++ library code designed to augment the C++ standard library. The Abseil library code is collected from Google's own C++ code base, has been extensively tested and used in production, and is the same code we depend on in our daily coding lives.  
  In some cases, Abseil provides pieces missing from the C++ standard; in others, Abseil provides alternatives to the standard for special needs we've found through usage in the Google code base. We denote those cases clearly within the library code we provide you.  
  Abseil is not meant to be a competitor to the standard library; we've just found that many of these utilities serve a purpose within our code base, and we now want to provide those resources to the C++ community as a whole.  
control: vcpkg/ports/abseil/CONTROL

Source: ace  
Version: 6.5.6  
Homepage: https://www.dre.vanderbilt.edu/~schmidt/ACE.html  
Description: The ADAPTIVE Communication Environment  
  
Feature: wchar  
Description: Enable extra wide char functions in ACE  
  
Feature: ssl  
Description: Enable SSL/TLS features in ACE  
Build-Depends: openssl  
  
Feature: xml  
Description: Enable XML features in ACE  
control: vcpkg/ports/ace/CONTROL

Source: activemq-cpp  
Version: 3.9.5  
Build-Depends: apr  
Description: Apache ActiveMQ is the most popular and powerful open source messaging and Integration Patterns server.  
control: vcpkg/ports/activemq-cpp/CONTROL

Source: ade  
Version: 0.1.1f  
Description: ADE Framework is a graph construction, manipulation, and processing framework. ADE Framework is suitable for organizing data flow processing and execution.  
control: vcpkg/ports/ade/CONTROL

Source: aixlog  
Version: 1.2.1-1  
Description: Header-only C++ logging library   
control: vcpkg/ports/aixlog/CONTROL

Source: alac  
Version:  2017-11-03-c38887c5-1  
Homepage: https://github.com/macosforge/alac  
Description: The Apple Lossless Audio Codec (ALAC) is a lossless audio codec developed by Apple and deployed on all of its platforms and devices.  
control: vcpkg/ports/alac/CONTROL

Source: alac-decoder  
Version: 0.2-1  
Homepage: https://distfiles.macports.org/alac_decoder  
Description:  ALAC C implementation of a decoder, written from reverse engineering the file format  
control: vcpkg/ports/alac-decoder/CONTROL

Source: alembic  
Version: 1.7.11-5  
Build-Depends: ilmbase, hdf5  
Description: Alembic is an open framework for storing and sharing scene data that includes a C++ library, a file format, and client plugins and applications.  
Homepage: https://alembic.io/  
control: vcpkg/ports/alembic/CONTROL

Source: aliyun-oss-c-sdk  
Version: 3.7.1-1  
Description: Alibaba Cloud Object Storage Service (OSS) is a cloud storage service provided by Alibaba Cloud, featuring massive capacity, security, a low cost, and high reliability.  
Build-Depends: curl, apr-util  
control: vcpkg/ports/aliyun-oss-c-sdk/CONTROL

Source: allegro5  
Version: 5.2.5.0  
Homepage: https://github.com/liballeg/allegro5  
Description: Allegro is a cross-platform library mainly aimed at video game and multimedia programming. It handles common, low-level tasks such as creating windows, accepting user input, loading data, drawing images, playing sounds, etc. and generally abstracting away the underlying platform. However, Allegro is not a game engine: you are free to design and structure your program as you like.  
Build-Depends: opengl, zlib, freetype, libogg, libvorbis, libflac, openal-soft, libpng, bzip2, physfs, libtheora, opus, opusfile  
control: vcpkg/ports/allegro5/CONTROL

Source: ampl-mp  
Version: 2019-03-21-1  
Description: An open-source library for mathematical programming  
control: vcpkg/ports/ampl-mp/CONTROL

Source: amqpcpp  
Version: 4.1.5  
Description: AMQP-CPP is a C++ library for communicating with a RabbitMQ message broker  
Build-Depends: openssl (linux)  
control: vcpkg/ports/amqpcpp/CONTROL

Source: anax  
Version: 2.1.0-6  
Description: An open source C++ entity system.  
Homepage: https://github.com/miguelmartin75/anax  
control: vcpkg/ports/anax/CONTROL

Source: angelscript  
Version: 2.33.1-1  
Description: The AngelCode Scripting Library, or AngelScript as it is also known, is an extremely flexible cross-platform scripting library designed to allow applications to extend their functionality through external scripts. It has been designed from the beginning to be an easy to use component, both for the application programmer and the script writer.  
  
Feature: addons  
Description: Installs all addons for use in compiling scripts addons  
control: vcpkg/ports/angelscript/CONTROL

Source: angle  
Version: 2019-07-19-2  
Homepage: https://github.com/google/angle  
Description: A conformant OpenGL ES implementation for Windows, Mac and Linux.  
  The goal of ANGLE is to allow users of multiple operating systems to seamlessly run WebGL and other OpenGL ES content by translating OpenGL ES API calls to one of the hardware-supported APIs available for that platform. ANGLE currently provides translation from OpenGL ES 2.0 and 3.0 to desktop OpenGL, OpenGL ES, Direct3D 9, and Direct3D 11. Support for translation from OpenGL ES to Vulkan is underway, and future plans include compute shader support (ES 3.1) and MacOS support.  
Build-Depends: egl-registry  
control: vcpkg/ports/angle/CONTROL

Source: antlr4  
Version: 4.7.1-3  
Homepage: https://www.antlr.org  
Description: ANother Tool for Language Recognition  
Build-Depends: libuuid (!uwp&!windows&!osx)  
control: vcpkg/ports/antlr4/CONTROL

Source: any-lite  
Version: 0.2.0  
Description: A C++17-like any, a type-safe container for single values of any type for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/any-lite/CONTROL

Source: anyrpc  
Version: 2017-12-01  
Homepage: https://github.com/sgieseking/anyrpc  
Description: A multiprotocol remote procedure call system for C++.  
control: vcpkg/ports/anyrpc/CONTROL

Source: apr  
Version: 1.6.5-2  
Homepage: https://apr.apache.org/  
Description: The Apache Portable Runtime (APR) is a C library that forms a system portability layer that covers many operating systems.  
  
Feature: private-headers  
Description: Install non-standard files required for building Apache httpd  
control: vcpkg/ports/apr/CONTROL

Source: apr-util  
Version: 1.6.0-3  
Homepage: https://apr.apache.org/  
Description: Apache Portable Runtime (APR) project  mission is to create and maintain software libraries that provide a predictable and consistent interface to underlying platform-specific implementation  
Build-Depends: expat, apr, openssl  
control: vcpkg/ports/apr-util/CONTROL

Source: arb  
Version: 2.16.0  
Homepage: https://github.com/fredrik-johansson/arb  
Description: a C library for arbitrary-precision interval arithmetic  
Build-Depends: flint  
control: vcpkg/ports/arb/CONTROL

Source: argagg  
Version: 0.4.6  
Description: A simple C++11 command line argument parser  
control: vcpkg/ports/argagg/CONTROL

Source: argh  
Version: 2018-12-18-1  
Description: Argh! A minimalist argument handler.  
control: vcpkg/ports/argh/CONTROL

Source: argparse  
Version: 1.9  
Description: Argument parser for modern C++  
Homepage: https://github.com/p-ranav/argparse  
control: vcpkg/ports/argparse/CONTROL

Source: args  
Version: 2019-07-11  
Homepage: https://github.com/Taywee/args  
Description: A simple header-only C++ argument parser library.  
control: vcpkg/ports/args/CONTROL

Source: argtable2  
Version: 2.13-2  
Description: Argtable is an ANSI C library for parsing GNU style command line options with a minimum of fuss.  
control: vcpkg/ports/argtable2/CONTROL

Source: argtable3  
Version: 2019-08-21  
Description: A single-file, ANSI C, command-line parsing library that parses GNU-style command-line options  
Homepage: www.argtable.org  
control: vcpkg/ports/argtable3/CONTROL

Source: armadillo  
Version: 2019-04-16-5  
Description: Armadillo is a high quality linear algebra library (matrix maths) for the C++ language, aiming towards a good balance between speed and ease of use  
Build-Depends: openblas (!osx), clapack (!osx)  
control: vcpkg/ports/armadillo/CONTROL

Source: arrow  
Version: 0.14.1-1  
Build-Depends: boost-system, boost-filesystem, boost-multiprecision, boost-algorithm, flatbuffers, rapidjson, zlib, lz4, brotli, zstd, snappy, gflags, thrift, double-conversion, glog, uriparser  
Homepage: https://github.com/apache/arrow  
Description: Apache Arrow is a columnar in-memory analytics layer designed to accelerate big data. It houses a set of canonical in-memory representations of flat and hierarchical data along with multiple language-bindings for structure manipulation. It also provides IPC and common algorithm implementations.  
control: vcpkg/ports/arrow/CONTROL

Source: asio  
Version: 1.12.2-2  
Homepage: https://github.com/chriskohlhoff/asio  
Description: Asio is a cross-platform C++ library for network and low-level I/O programming that provides developers with a consistent asynchronous model using a modern C++ approach.  
control: vcpkg/ports/asio/CONTROL

Source: asmjit  
Version: 2019-07-11  
Homepage: https://github.com/asmjit/asmjit  
Description: Complete x86/x64 JIT and Remote Assembler for C++  
control: vcpkg/ports/asmjit/CONTROL

Source: assimp  
Version: 5.0.0  
Homepage: https://github.com/assimp/assimp  
Description: The Open Asset import library  
Build-Depends: zlib, rapidjson  
control: vcpkg/ports/assimp/CONTROL

Source: asynch  
Version: 2019-09-21-1  
Homepage: https://github.com/naasking/async.h  
Description: Async.h - asynchronous, stackless subroutines.  
control: vcpkg/ports/asynch/CONTROL

Source: asyncplusplus  
Version: 1.0-1  
Description: Async++ is a lightweight concurrency framework for C++11  
control: vcpkg/ports/asyncplusplus/CONTROL

Source: atk  
Version: 2.24.0-4  
Homepage: https://developer.gnome.org/atk/  
Description: GNOME Accessibility Toolkit  
Build-Depends: glib, gettext  
control: vcpkg/ports/atk/CONTROL

Source: atkmm  
Version: 2.24.2-1  
Homepage: https://www.gtkmm.org  
Description: atkmm is the official C++ interface for the ATK accessibility toolkit library. It may be used, for instance, by user interfaces implemented with gtkmm.  
Build-Depends: glib, gettext, atk, glibmm  
control: vcpkg/ports/atkmm/CONTROL

Source: atlmfc  
Version: 0  
Description: a stub package that ensures VS has ATL/MFC installed.  
control: vcpkg/ports/atlmfc/CONTROL

Source: aubio  
Version: 0.4.9  
Homepage: https://github.com/aubio/aubio  
Description: Aubio is a tool designed for the extraction of annotations from audio signals. Its features include segmenting a sound file before each of its attacks, performing pitch detection, tapping the beat and producing midi streams from live audio.  
Build-Depends: ffmpeg, libsndfile, libogg, libflac, libvorbis, bzip2, liblzma  
control: vcpkg/ports/aubio/CONTROL

Source: aurora  
Version: 2017-06-21-c75699d2a8caa726260c29b6d7a0fd35f8f28933  
Homepage: https://github.com/Bromeon/Aurora  
Description: Aurora is an open-source C++ library providing various rather uncommon C++ utilities  
control: vcpkg/ports/aurora/CONTROL

Source: autobahn  
Version: 18.4.1  
Build-Depends: websocketpp, msgpack, boost-asio, boost-thread  
Description: WAMP for C++ in Boost/Asio   
Homepage: https://crossbar.io/autobahn  
control: vcpkg/ports/autobahn/CONTROL

Source: avro-c  
Version: 1.8.2-3  
Homepage: https://github.com/apache/avro  
Description: Apache Avro is a data serialization system  
Build-Depends: jansson, liblzma, zlib  
control: vcpkg/ports/avro-c/CONTROL

Source: aws-c-common  
Version: 0.4.1  
Description: AWS common library for C  
control: vcpkg/ports/aws-c-common/CONTROL

Source: aws-c-event-stream  
Version: 0.1.1  
Description: C99 implementation of the vnd.amazon.event-stream content-type.  
Build-Depends: aws-c-common, aws-checksums  
control: vcpkg/ports/aws-c-event-stream/CONTROL

Source: aws-checksums  
Version: 0.1.3  
Description: Cross-Platform HW accelerated CRC32c and CRC32 with fallback to efficient SW implementations.  
control: vcpkg/ports/aws-checksums/CONTROL

Source: aws-lambda-cpp  
Version: 0.1.0-2  
Build-Depends: curl  
Description: C++ Runtime for AWS Lambda.  
control: vcpkg/ports/aws-lambda-cpp/CONTROL

Source: aws-sdk-cpp  
Version: 1.7.142-1  
Homepage: https://github.com/aws/aws-sdk-cpp  
Description: AWS SDK for C++  
Build-Depends: openssl (!uwp&!windows), curl (!uwp&!windows), aws-c-event-stream  
Default-Features: dynamodb, s3, kinesis  
# Automatically generated by generateFeatures.ps1  
  
Feature: access-management  
Description: C++ SDK for the AWS access-management service  
  
Feature: acm  
Description: C++ SDK for the AWS acm service  
  
Feature: acm-pca  
Description: C++ SDK for the AWS acm-pca service  
  
Feature: alexaforbusiness  
Description: C++ SDK for the AWS alexaforbusiness service  
  
Feature: amplify  
Description: C++ SDK for the AWS amplify service  
  
Feature: apigateway  
Description: C++ SDK for the AWS apigateway service  
  
Feature: apigatewaymanagementapi  
Description: C++ SDK for the AWS apigatewaymanagementapi service  
  
Feature: apigatewayv2  
Description: C++ SDK for the AWS apigatewayv2 service  
  
Feature: application-autoscaling  
Description: C++ SDK for the AWS application-autoscaling service  
  
Feature: appmesh  
Description: C++ SDK for the AWS appmesh service  
  
Feature: appstream  
Description: C++ SDK for the AWS appstream service  
  
Feature: appsync  
Description: C++ SDK for the AWS appsync service  
  
Feature: athena  
Description: C++ SDK for the AWS athena service  
  
Feature: autoscaling  
Description: C++ SDK for the AWS autoscaling service  
  
Feature: autoscaling-plans  
Description: C++ SDK for the AWS autoscaling-plans service  
  
Feature: AWSMigrationHub  
Description: C++ SDK for the AWS AWSMigrationHub service  
  
Feature: awstransfer  
Description: C++ SDK for the AWS awstransfer service  
  
Feature: backup  
Description: C++ SDK for the AWS backup service  
  
Feature: batch  
Description: C++ SDK for the AWS batch service  
  
Feature: budgets  
Description: C++ SDK for the AWS budgets service  
  
Feature: ce  
Description: C++ SDK for the AWS ce service  
  
Feature: chime  
Description: C++ SDK for the AWS chime service  
  
Feature: cloud9  
Description: C++ SDK for the AWS cloud9 service  
  
Feature: clouddirectory  
Description: C++ SDK for the AWS clouddirectory service  
  
Feature: cloudformation  
Description: C++ SDK for the AWS cloudformation service  
  
Feature: cloudfront  
Description: C++ SDK for the AWS cloudfront service  
  
Feature: cloudhsm  
Description: C++ SDK for the AWS cloudhsm service  
  
Feature: cloudhsmv2  
Description: C++ SDK for the AWS cloudhsmv2 service  
  
Feature: cloudsearch  
Description: C++ SDK for the AWS cloudsearch service  
  
Feature: cloudsearchdomain  
Description: C++ SDK for the AWS cloudsearchdomain service  
  
Feature: cloudtrail  
Description: C++ SDK for the AWS cloudtrail service  
  
Feature: codebuild  
Description: C++ SDK for the AWS codebuild service  
  
Feature: codecommit  
Description: C++ SDK for the AWS codecommit service  
  
Feature: codedeploy  
Description: C++ SDK for the AWS codedeploy service  
  
Feature: codepipeline  
Description: C++ SDK for the AWS codepipeline service  
  
Feature: codestar  
Description: C++ SDK for the AWS codestar service  
  
Feature: cognito-identity  
Description: C++ SDK for the AWS cognito-identity service  
  
Feature: cognito-idp  
Description: C++ SDK for the AWS cognito-idp service  
  
Feature: cognito-sync  
Description: C++ SDK for the AWS cognito-sync service  
  
Feature: comprehend  
Description: C++ SDK for the AWS comprehend service  
  
Feature: comprehendmedical  
Description: C++ SDK for the AWS comprehendmedical service  
  
Feature: config  
Description: C++ SDK for the AWS config service  
  
Feature: connect  
Description: C++ SDK for the AWS connect service  
  
Feature: cur  
Description: C++ SDK for the AWS cur service  
  
Feature: datapipeline  
Description: C++ SDK for the AWS datapipeline service  
  
Feature: datasync  
Description: C++ SDK for the AWS datasync service  
  
Feature: dax  
Description: C++ SDK for the AWS dax service  
  
Feature: devicefarm  
Description: C++ SDK for the AWS devicefarm service  
  
Feature: directconnect  
Description: C++ SDK for the AWS directconnect service  
  
Feature: discovery  
Description: C++ SDK for the AWS discovery service  
  
Feature: dlm  
Description: C++ SDK for the AWS dlm service  
  
Feature: dms  
Description: C++ SDK for the AWS dms service  
  
Feature: docdb  
Description: C++ SDK for the AWS docdb service  
  
Feature: ds  
Description: C++ SDK for the AWS ds service  
  
Feature: dynamodb  
Description: C++ SDK for the AWS dynamodb service  
  
Feature: dynamodbstreams  
Description: C++ SDK for the AWS dynamodbstreams service  
  
Feature: ec2  
Description: C++ SDK for the AWS ec2 service  
  
Feature: ecr  
Description: C++ SDK for the AWS ecr service  
  
Feature: ecs  
Description: C++ SDK for the AWS ecs service  
  
Feature: eks  
Description: C++ SDK for the AWS eks service  
  
Feature: elasticache  
Description: C++ SDK for the AWS elasticache service  
  
Feature: elasticbeanstalk  
Description: C++ SDK for the AWS elasticbeanstalk service  
  
Feature: elasticfilesystem  
Description: C++ SDK for the AWS elasticfilesystem service  
  
Feature: elasticloadbalancing  
Description: C++ SDK for the AWS elasticloadbalancing service  
  
Feature: elasticloadbalancingv2  
Description: C++ SDK for the AWS elasticloadbalancingv2 service  
  
Feature: elasticmapreduce  
Description: C++ SDK for the AWS elasticmapreduce service  
  
Feature: elastictranscoder  
Description: C++ SDK for the AWS elastictranscoder service  
  
Feature: email  
Description: C++ SDK for the AWS email service  
  
Feature: es  
Description: C++ SDK for the AWS es service  
  
Feature: events  
Description: C++ SDK for the AWS events service  
  
Feature: firehose  
Description: C++ SDK for the AWS firehose service  
  
Feature: fms  
Description: C++ SDK for the AWS fms service  
  
Feature: fsx  
Description: C++ SDK for the AWS fsx service  
  
Feature: gamelift  
Description: C++ SDK for the AWS gamelift service  
  
Feature: glacier  
Description: C++ SDK for the AWS glacier service  
  
Feature: globalaccelerator  
Description: C++ SDK for the AWS globalaccelerator service  
  
Feature: glue  
Description: C++ SDK for the AWS glue service  
  
Feature: greengrass  
Description: C++ SDK for the AWS greengrass service  
  
Feature: guardduty  
Description: C++ SDK for the AWS guardduty service  
  
Feature: health  
Description: C++ SDK for the AWS health service  
  
Feature: iam  
Description: C++ SDK for the AWS iam service  
  
Feature: identity-management  
Description: C++ SDK for the AWS identity-management service  
  
Feature: importexport  
Description: C++ SDK for the AWS importexport service  
  
Feature: inspector  
Description: C++ SDK for the AWS inspector service  
  
Feature: iot  
Description: C++ SDK for the AWS iot service  
  
Feature: iot-data  
Description: C++ SDK for the AWS iot-data service  
  
Feature: iot-jobs-data  
Description: C++ SDK for the AWS iot-jobs-data service  
  
Feature: iot1click-devices  
Description: C++ SDK for the AWS iot1click-devices service  
  
Feature: iot1click-projects  
Description: C++ SDK for the AWS iot1click-projects service  
  
Feature: iotanalytics  
Description: C++ SDK for the AWS iotanalytics service  
  
Feature: kafka  
Description: C++ SDK for the AWS kafka service  
  
Feature: kinesis  
Description: C++ SDK for the AWS kinesis service  
  
Feature: kinesis-video-archived-media  
Description: C++ SDK for the AWS kinesis-video-archived-media service  
  
Feature: kinesis-video-media  
Description: C++ SDK for the AWS kinesis-video-media service  
  
Feature: kinesisanalytics  
Description: C++ SDK for the AWS kinesisanalytics service  
  
Feature: kinesisanalyticsv2  
Description: C++ SDK for the AWS kinesisanalyticsv2 service  
  
Feature: kinesisvideo  
Description: C++ SDK for the AWS kinesisvideo service  
  
Feature: kms  
Description: C++ SDK for the AWS kms service  
  
Feature: lambda  
Description: C++ SDK for the AWS lambda service  
  
Feature: lex  
Description: C++ SDK for the AWS lex service  
  
Feature: lex-models  
Description: C++ SDK for the AWS lex-models service  
  
Feature: license-manager  
Description: C++ SDK for the AWS license-manager service  
  
Feature: lightsail  
Description: C++ SDK for the AWS lightsail service  
  
Feature: logs  
Description: C++ SDK for the AWS logs service  
  
Feature: machinelearning  
Description: C++ SDK for the AWS machinelearning service  
  
Feature: macie  
Description: C++ SDK for the AWS macie service  
  
Feature: marketplace-entitlement  
Description: C++ SDK for the AWS marketplace-entitlement service  
  
Feature: marketplacecommerceanalytics  
Description: C++ SDK for the AWS marketplacecommerceanalytics service  
  
Feature: mediaconnect  
Description: C++ SDK for the AWS mediaconnect service  
  
Feature: mediaconvert  
Description: C++ SDK for the AWS mediaconvert service  
  
Feature: medialive  
Description: C++ SDK for the AWS medialive service  
  
Feature: mediapackage  
Description: C++ SDK for the AWS mediapackage service  
  
Feature: mediastore  
Description: C++ SDK for the AWS mediastore service  
  
Feature: mediastore-data  
Description: C++ SDK for the AWS mediastore-data service  
  
Feature: mediatailor  
Description: C++ SDK for the AWS mediatailor service  
  
Feature: meteringmarketplace  
Description: C++ SDK for the AWS meteringmarketplace service  
  
Feature: mobile  
Description: C++ SDK for the AWS mobile service  
  
Feature: mobileanalytics  
Description: C++ SDK for the AWS mobileanalytics service  
  
Feature: monitoring  
Description: C++ SDK for the AWS monitoring service  
  
Feature: mq  
Description: C++ SDK for the AWS mq service  
  
Feature: mturk-requester  
Description: C++ SDK for the AWS mturk-requester service  
  
Feature: neptune  
Description: C++ SDK for the AWS neptune service  
  
Feature: opsworks  
Description: C++ SDK for the AWS opsworks service  
  
Feature: opsworkscm  
Description: C++ SDK for the AWS opsworkscm service  
  
Feature: organizations  
Description: C++ SDK for the AWS organizations service  
  
Feature: pi  
Description: C++ SDK for the AWS pi service  
  
Feature: pinpoint  
Description: C++ SDK for the AWS pinpoint service  
  
Feature: pinpoint-email  
Description: C++ SDK for the AWS pinpoint-email service  
  
Feature: polly  
Description: C++ SDK for the AWS polly service  
  
Feature: pricing  
Description: C++ SDK for the AWS pricing service  
  
Feature: queues  
Description: C++ SDK for the AWS queues service  
  
Feature: quicksight  
Description: C++ SDK for the AWS quicksight service  
  
Feature: ram  
Description: C++ SDK for the AWS ram service  
  
Feature: rds  
Description: C++ SDK for the AWS rds service  
  
Feature: rds-data  
Description: C++ SDK for the AWS rds-data service  
  
Feature: redshift  
Description: C++ SDK for the AWS redshift service  
  
Feature: rekognition  
Description: C++ SDK for the AWS rekognition service  
  
Feature: resource-groups  
Description: C++ SDK for the AWS resource-groups service  
  
Feature: resourcegroupstaggingapi  
Description: C++ SDK for the AWS resourcegroupstaggingapi service  
  
Feature: robomaker  
Description: C++ SDK for the AWS robomaker service  
  
Feature: route53  
Description: C++ SDK for the AWS route53 service  
  
Feature: route53domains  
Description: C++ SDK for the AWS route53domains service  
  
Feature: route53resolver  
Description: C++ SDK for the AWS route53resolver service  
  
Feature: s3  
Description: C++ SDK for the AWS s3 service  
  
Feature: s3-encryption  
Description: C++ SDK for the AWS s3-encryption service  
  
Feature: s3control  
Description: C++ SDK for the AWS s3control service  
  
Feature: sagemaker  
Description: C++ SDK for the AWS sagemaker service  
  
Feature: sagemaker-runtime  
Description: C++ SDK for the AWS sagemaker-runtime service  
  
Feature: sdb  
Description: C++ SDK for the AWS sdb service  
  
Feature: secretsmanager  
Description: C++ SDK for the AWS secretsmanager service  
  
Feature: securityhub  
Description: C++ SDK for the AWS securityhub service  
  
Feature: serverlessrepo  
Description: C++ SDK for the AWS serverlessrepo service  
  
Feature: servicecatalog  
Description: C++ SDK for the AWS servicecatalog service  
  
Feature: servicediscovery  
Description: C++ SDK for the AWS servicediscovery service  
  
Feature: shield  
Description: C++ SDK for the AWS shield service  
  
Feature: signer  
Description: C++ SDK for the AWS signer service  
  
Feature: sms  
Description: C++ SDK for the AWS sms service  
  
Feature: sms-voice  
Description: C++ SDK for the AWS sms-voice service  
  
Feature: snowball  
Description: C++ SDK for the AWS snowball service  
  
Feature: sns  
Description: C++ SDK for the AWS sns service  
  
Feature: sqs  
Description: C++ SDK for the AWS sqs service  
  
Feature: ssm  
Description: C++ SDK for the AWS ssm service  
  
Feature: states  
Description: C++ SDK for the AWS states service  
  
Feature: storagegateway  
Description: C++ SDK for the AWS storagegateway service  
  
Feature: sts  
Description: C++ SDK for the AWS sts service  
  
Feature: support  
Description: C++ SDK for the AWS support service  
  
Feature: swf  
Description: C++ SDK for the AWS swf service  
  
Feature: text-to-speech  
Description: C++ SDK for the AWS text-to-speech service  
  
Feature: transcribe  
Description: C++ SDK for the AWS transcribe service  
  
Feature: transfer  
Description: C++ SDK for the AWS transfer service  
  
Feature: translate  
Description: C++ SDK for the AWS translate service  
  
Feature: waf  
Description: C++ SDK for the AWS waf service  
  
Feature: waf-regional  
Description: C++ SDK for the AWS waf-regional service  
  
Feature: workdocs  
Description: C++ SDK for the AWS workdocs service  
  
Feature: workmail  
Description: C++ SDK for the AWS workmail service  
  
Feature: workspaces  
Description: C++ SDK for the AWS workspaces service  
  
Feature: xray  
Description: C++ SDK for the AWS xray service  
control: vcpkg/ports/aws-sdk-cpp/CONTROL

Source: azmq  
Version: 1.0.2  
Build-Depends: boost-asio, boost-assert, boost-config, boost-container, boost-format, boost-intrusive, boost-iterator, boost-lexical-cast, boost-logic, boost-optional, boost-random, boost-range, boost-regex, boost-system, boost-thread, boost-utility, zeromq  
Description: Boost Asio style bindings for ZeroMQ  
  This library is built on top of ZeroMQ's standard C interface and is intended to work well with C++ applications which use the Boost libraries in general, and Asio in particular.  
  The main abstraction exposed by the library is azmq::socket which provides an Asio style socket interface to the underlying zeromq socket and interfaces with Asio's io_service(). The socket implementation participates in the io_service's reactor for asynchronous IO and may be freely mixed with other Asio socket types (raw TCP/UDP/Serial/etc.).  
control: vcpkg/ports/azmq/CONTROL

Source: azure-c-shared-utility  
Version: 2019-08-20.1  
Description: Azure C SDKs common code  
Build-Depends: curl (linux), openssl (linux), azure-macro-utils-c, umock-c  
  
Feature: public-preview  
Description: Azure C SDKs common code (public preview)  
control: vcpkg/ports/azure-c-shared-utility/CONTROL

Source: azure-iot-sdk-c  
Version: 2019-08-20.1  
Build-Depends: azure-uamqp-c, azure-umqtt-c, azure-c-shared-utility, parson, azure-uhttp-c, azure-macro-utils-c, umock-c  
Description: A C99 SDK for connecting devices to Microsoft Azure IoT services   
  
Feature: public-preview  
Description: A version of the azure-iot-sdk-c containing public-preview features.  
Build-Depends: azure-uamqp-c[public-preview], azure-umqtt-c[public-preview], azure-c-shared-utility[public-preview], azure-uhttp-c[public-preview], azure-macro-utils-c, umock-c  
control: vcpkg/ports/azure-iot-sdk-c/CONTROL

Source: azure-macro-utils-c  
Version: 2019-08-20.1  
Description: A library of macros for the Azure IoT SDK Suite  
Build-Depends:   
  
control: vcpkg/ports/azure-macro-utils-c/CONTROL

Source: azure-storage-cpp  
Version: 6.1.0-2  
Build-Depends: cpprestsdk[core], atlmfc (windows), boost-log (!windows&!uwp), boost-locale (!windows&!uwp), libxml2 (!windows&!uwp), libuuid (!windows&!uwp&!osx), gettext  
Description: Microsoft Azure Storage Client SDK for C++  
  A client library for working with Microsoft Azure storage services including blobs, files, tables, and queues. This client library enables working with the Microsoft Azure storage services which include the blob service for storing binary and text data, the file service for storing binary and text data, the table service for storing structured non-relational data, and the queue service for storing messages that may be accessed by a client.  
Homepage: https://blogs.msdn.com/b/windowsazurestorage/  
control: vcpkg/ports/azure-storage-cpp/CONTROL

Source: azure-uamqp-c  
Version: 2019-08-20.1  
Build-Depends: azure-c-shared-utility, azure-macro-utils-c, umock-c  
Description: AMQP library for C  
  
Feature: public-preview  
Description: AMQP library for C (public preview)  
Build-Depends: azure-c-shared-utility[public-preview], azure-macro-utils-c, umock-c  
control: vcpkg/ports/azure-uamqp-c/CONTROL

Source: azure-uhttp-c  
Version: 2019-08-20.1  
Build-Depends: azure-c-shared-utility, azure-macro-utils-c, umock-c  
Description: Azure HTTP Library written in C  
  
Feature: public-preview  
Description: Azure HTTP Library written in C (public preview)  
Build-Depends: azure-c-shared-utility[public-preview], azure-macro-utils-c, umock-c  
control: vcpkg/ports/azure-uhttp-c/CONTROL

Source: azure-umqtt-c  
Version: 2019-08-20.1  
Build-Depends: azure-c-shared-utility, azure-macro-utils-c, umock-c  
Description: General purpose library for communication over the mqtt protocol  
  
Feature: public-preview  
Description: General purpose library for communication over the mqtt protocol (public preview)  
Build-Depends: azure-c-shared-utility[public-preview], azure-macro-utils-c, umock-c  
control: vcpkg/ports/azure-umqtt-c/CONTROL

Source: basisu  
Version: 1.11-2  
Homepage: https://github.com/BinomialLLC/basis_universal  
Description: Basis Universal is a supercompressed GPU texture and video compression format that outputs a highly compressed intermediate file format (.basis) that can be quickly transcoded to a wide variety of GPU texture compression formats.   
Build-Depends: lodepng  
  
control: vcpkg/ports/basisu/CONTROL

Source: bde  
Version: 3.2.0.0-1  
Description: Basic Development Environment - a set of foundational C++ libraries used at Bloomberg.  
control: vcpkg/ports/bde/CONTROL

Source: bdwgc  
Version: 8.0.4-1  
Description: The Boehm-Demers-Weiser conservative C/C++ Garbage Collector (libgc, bdwgc, boehm-gc)  
control: vcpkg/ports/bdwgc/CONTROL

Source: beast  
Version: 0  
Homepage: https://www.boost.org/doc/libs/release/libs/beast/  
Build-Depends: boost-beast  
Description: HTTP/1 and WebSocket, header-only using Boost.Asio and C++11  
control: vcpkg/ports/beast/CONTROL

Source: benchmark  
Version: 1.5  
Homepage: https://github.com/google/benchmark  
Description: A library to support the benchmarking of functions, similar to unit-tests.  
control: vcpkg/ports/benchmark/CONTROL

Source: bento4  
Version: 1.5.1-628  
Homepage: https://github.com/axiomatic-systems/Bento4  
Description: Bento4 is a C++ class library and tools designed to read and write ISO-MP4 files. This format is defined in international specifications ISO/IEC 14496-12, 14496-14 and 14496-15.  
  
control: vcpkg/ports/bento4/CONTROL

Source: berkeleydb  
Version: 4.8.30-2  
Homepage: https://download.oracle.com/  
Description: BDB - A high-performance embedded database for key/value data.  
control: vcpkg/ports/berkeleydb/CONTROL

Source: bigint  
Version: 2010.04.30-3  
Homepage: https://mattmccutchen.net/bigint  
Description: C++ Big Integer Library  
control: vcpkg/ports/bigint/CONTROL

Source: binn  
Version: 1.0  
Description: Binn is a binary data serialization format designed to be compact, fast and easy to use.  
control: vcpkg/ports/binn/CONTROL

Source: bitserializer  
Version: 0.8  
Description: The core part of library for serialization of arbitrary C++ types to various output formats.  
control: vcpkg/ports/bitserializer/CONTROL

Source: bitserializer-cpprestjson  
Version: 0.8  
Build-Depends: bitserializer, cpprestsdk  
Description: This is an implementation of the BitSerializer archive for serialization JSON (based on CppRestSDK library).  
control: vcpkg/ports/bitserializer-cpprestjson/CONTROL

Source: bitserializer-rapidjson  
Version: 0.8  
Build-Depends: bitserializer, rapidjson  
Description: This is an implementation of the BitSerializer archive for serialization JSON (based on the RapidJson library).  
control: vcpkg/ports/bitserializer-rapidjson/CONTROL

Source: bitsery  
Version: 5.0.0  
Description: Header only C++ binary serialization library  
control: vcpkg/ports/bitsery/CONTROL

Source: blaze  
Version: 3.6  
Build-Depends: clapack (!osx), boost-exception  
Homepage: https://bitbucket.org/blaze-lib/blaze  
Description: Blaze is an open-source, high-performance C++ math library for dense and sparse arithmetic.  
control: vcpkg/ports/blaze/CONTROL

Source: blend2d  
Version: beta_2019-10-09  
Description: Beta 2D Vector Graphics Powered by a JIT Compiler  
Default-Features: jit, logging  
  
Feature: jit  
Description: Default feature. Enables jit pipeline compilation. Not supported for ARM and UWP.  
  
Feature: logging  
Description: Default feature. Enables logging.  
control: vcpkg/ports/blend2d/CONTROL

Source: blosc  
Version: 1.17.0-1  
Build-Depends: lz4, snappy, zlib, zstd  
Homepage: https://github.com/Blosc/c-blosc  
Description: A blocking, shuffling and loss-less compression library that can be faster than `memcpy()`  
control: vcpkg/ports/blosc/CONTROL

Source: bond  
Maintainer: bond@microsoft.com  
Version: 8.1.0-2  
Description: Bond is a cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.  
Homepage: https://github.com/Microsoft/bond  
Build-Depends: rapidjson, boost-config, boost-utility, boost-assign  
control: vcpkg/ports/bond/CONTROL

Source: boolinq  
Version: 2019-07-22  
Description: Super tiny C++11 single-file header-only LINQ library  
Homepage: https://github.com/k06a/boolinq  
control: vcpkg/ports/boolinq/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost  
Version: 1.71.0  
Homepage: https://boost.org  
Description: Peer-reviewed portable C++ source libraries  
Build-Depends: boost-accumulators, boost-algorithm, boost-align, boost-any, boost-array, boost-asio, boost-assert, boost-assign, boost-atomic, boost-beast, boost-bimap, boost-bind, boost-callable-traits, boost-chrono, boost-circular-buffer, boost-compatibility, boost-compute, boost-concept-check, boost-config, boost-container, boost-container-hash, boost-context (!uwp), boost-contract (!arm), boost-conversion, boost-convert, boost-core, boost-coroutine (!uwp), boost-coroutine2, boost-crc, boost-date-time, boost-detail, boost-disjoint-sets, boost-dll, boost-dynamic-bitset, boost-endian, boost-exception, boost-fiber (windows), boost-filesystem (!uwp), boost-flyweight, boost-foreach, boost-format, boost-function, boost-functional, boost-function-types, boost-fusion, boost-geometry, boost-gil, boost-graph, boost-graph-parallel, boost-hana, boost-heap, boost-histogram, boost-hof, boost-icl, boost-integer, boost-interprocess, boost-intrusive, boost-io, boost-iostreams (!uwp), boost-iterator, boost-lambda, boost-lexical-cast, boost-locale (!uwp), boost-local-function, boost-lockfree, boost-log (!uwp), boost-logic, boost-math, boost-metaparse, boost-move, boost-mp11, boost-mpl, boost-msm, boost-multiprecision, boost-multi-array, boost-multi-index, boost-numeric-conversion, boost-interval, boost-odeint, boost-ublas, boost-safe-numerics, boost-optional, boost-outcome, boost-parameter, boost-parameter-python (windows), boost-phoenix, boost-polygon, boost-poly-collection, boost-pool, boost-predef, boost-preprocessor, boost-process, boost-program-options, boost-property-map, boost-property-tree, boost-proto, boost-ptr-container, boost-python (windows), boost-qvm, boost-random, boost-range, boost-ratio, boost-rational, boost-regex, boost-numeric-conversion, boost-interval, boost-odeint, boost-ublas, boost-safe-numerics, boost-scope-exit, boost-serialization, boost-signals2, boost-smart-ptr, boost-sort, boost-spirit, boost-stacktrace (!uwp), boost-statechart, boost-static-assert, boost-system, boost-test (!uwp), boost-thread, boost-throw-exception, boost-timer, boost-tokenizer, boost-tti, boost-tuple, boost-typeof, boost-type-erasure (!arm), boost-type-index, boost-type-traits, boost-units, boost-unordered, boost-utility, boost-uuid, boost-variant, boost-variant2, boost-vmd, boost-wave (!uwp), boost-winapi, boost-xpressive, boost-yap  
  
Feature: mpi  
Description: Build with MPI support  
Build-Depends: boost-mpi  
control: vcpkg/ports/boost/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-accumulators  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-circular-buffer, boost-concept-check, boost-config, boost-core, boost-detail, boost-fusion, boost-interval, boost-iterator, boost-mpl, boost-numeric-conversion, boost-odeint, boost-parameter, boost-preprocessor, boost-range, boost-serialization, boost-static-assert, boost-throw-exception, boost-tuple, boost-typeof, boost-type-traits, boost-ublas, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/accumulators  
Description: Boost accumulators module  
control: vcpkg/ports/boost-accumulators/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-algorithm  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-bind, boost-concept-check, boost-config, boost-core, boost-detail, boost-exception, boost-function, boost-iterator, boost-mpl, boost-range, boost-regex, boost-static-assert, boost-throw-exception, boost-tuple, boost-type-traits, boost-unordered, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/algorithm  
Description: Boost algorithm module  
control: vcpkg/ports/boost-algorithm/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-align  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-static-assert, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/align  
Description: Boost align module  
control: vcpkg/ports/boost-align/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-any  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-static-assert, boost-throw-exception, boost-type-index, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/any  
Description: Boost any module  
control: vcpkg/ports/boost-any/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-array  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-detail, boost-static-assert, boost-throw-exception, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/array  
Description: Boost array module  
control: vcpkg/ports/boost-array/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-asio  
Version: 1.71.0-1  
Build-Depends: boost-array, boost-assert, boost-bind, boost-chrono, boost-compatibility, boost-config, boost-coroutine (!uwp), boost-date-time, boost-detail, boost-function, boost-integer, boost-regex, boost-smart-ptr, boost-system, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers, openssl  
Homepage: https://github.com/boostorg/asio  
Description: Boost asio module  
control: vcpkg/ports/boost-asio/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-assert  
Version: 1.71.0  
Build-Depends: boost-config, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/assert  
Description: Boost assert module  
control: vcpkg/ports/boost-assert/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-assign  
Version: 1.71.0  
Build-Depends: boost-array, boost-config, boost-detail, boost-move, boost-mpl, boost-preprocessor, boost-ptr-container, boost-range, boost-static-assert, boost-throw-exception, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/assign  
Description: Boost assign module  
control: vcpkg/ports/boost-assign/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-atomic  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-integer, boost-modular-build-helper, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/atomic  
Description: Boost atomic module  
control: vcpkg/ports/boost-atomic/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-beast  
Version: 1.71.0  
Build-Depends: boost-asio, boost-assert, boost-bind, boost-config, boost-container, boost-core, boost-endian, boost-intrusive, boost-logic, boost-mp11, boost-optional, boost-smart-ptr, boost-static-assert, boost-system, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/beast  
Description: Boost beast module  
control: vcpkg/ports/boost-beast/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-bimap  
Version: 1.71.0  
Build-Depends: boost-concept-check, boost-config, boost-container-hash, boost-functional, boost-iterator, boost-lambda, boost-mpl, boost-multi-index, boost-preprocessor, boost-property-map, boost-serialization, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/bimap  
Description: Boost bimap module  
control: vcpkg/ports/boost-bimap/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-bind  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-detail, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/bind  
Description: Boost bind module  
control: vcpkg/ports/boost-bind/CONTROL

Source: boost-build  
Version: 1.70.0-1  
Homepage: https://github.com/boostorg/build  
Description: Boost.Build  
control: vcpkg/ports/boost-build/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-callable-traits  
Version: 1.71.0  
Build-Depends: boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/callable_traits  
Description: Boost callable_traits module  
control: vcpkg/ports/boost-callable-traits/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-chrono  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-detail, boost-integer, boost-modular-build-helper, boost-move, boost-mpl, boost-predef, boost-ratio, boost-static-assert, boost-system, boost-throw-exception, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/chrono  
Description: Boost chrono module  
control: vcpkg/ports/boost-chrono/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-circular-buffer  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-concept-check, boost-config, boost-core, boost-move, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/circular_buffer  
Description: Boost circular_buffer module  
control: vcpkg/ports/boost-circular-buffer/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-compatibility  
Version: 1.71.0  
Build-Depends: boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/compatibility  
Description: Boost compatibility module  
control: vcpkg/ports/boost-compatibility/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-compute  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-array, boost-assert, boost-chrono, boost-config, boost-core, boost-filesystem (!uwp), boost-function, boost-function-types, boost-fusion, boost-iterator, boost-lexical-cast, boost-math, boost-mpl, boost-optional, boost-preprocessor, boost-property-tree, boost-proto, boost-range, boost-smart-ptr, boost-static-assert, boost-thread, boost-throw-exception, boost-tuple, boost-typeof, boost-type-traits, boost-utility, boost-uuid, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/compute  
Description: Boost compute module  
control: vcpkg/ports/boost-compute/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-concept-check  
Version: 1.71.0  
Build-Depends: boost-config, boost-preprocessor, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/concept_check  
Description: Boost concept_check module  
control: vcpkg/ports/boost-concept-check/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-config  
Version: 1.71.0  
Build-Depends: boost-compatibility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/config  
Description: Boost config module  
control: vcpkg/ports/boost-config/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-container  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-container-hash, boost-core, boost-integer, boost-intrusive, boost-modular-build-helper, boost-move, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/container  
Description: Boost container module  
control: vcpkg/ports/boost-container/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-container-hash  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-core, boost-detail, boost-integer, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/container_hash  
Description: Boost container_hash module  
control: vcpkg/ports/boost-container-hash/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-context  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-detail, boost-integer, boost-modular-build-helper, boost-pool, boost-predef, boost-smart-ptr, boost-thread, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/context  
Description: Boost context module  
control: vcpkg/ports/boost-context/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-contract  
Version: 1.71.0  
Build-Depends: boost-any, boost-assert, boost-build, boost-config, boost-core, boost-detail, boost-exception, boost-function, boost-function-types, boost-modular-build-helper, boost-mpl, boost-optional, boost-preprocessor, boost-smart-ptr, boost-static-assert, boost-thread, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/contract  
Description: Boost contract module  
control: vcpkg/ports/boost-contract/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-conversion  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-throw-exception, boost-typeof, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/conversion  
Description: Boost conversion module  
control: vcpkg/ports/boost-conversion/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-convert  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-function-types, boost-lexical-cast, boost-math, boost-mpl, boost-optional, boost-parameter, boost-range, boost-spirit, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/convert  
Description: Boost convert module  
control: vcpkg/ports/boost-convert/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-core  
Version: 1.71.0  
Build-Depends: boost-config, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/core  
Description: Boost core module  
control: vcpkg/ports/boost-core/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-coroutine  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-context (!uwp), boost-detail, boost-exception, boost-integer, boost-modular-build-helper, boost-move, boost-range, boost-system, boost-thread, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/coroutine  
Description: Boost coroutine module  
control: vcpkg/ports/boost-coroutine/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-coroutine2  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-context (!uwp), boost-detail, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/coroutine2  
Description: Boost coroutine2 module  
control: vcpkg/ports/boost-coroutine2/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-crc  
Version: 1.71.0  
Build-Depends: boost-array, boost-compatibility, boost-config, boost-integer, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/crc  
Description: Boost crc module  
control: vcpkg/ports/boost-crc/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-date-time  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-assert, boost-build, boost-compatibility, boost-config, boost-core, boost-detail, boost-integer, boost-io, boost-lexical-cast, boost-math, boost-modular-build-helper, boost-mpl, boost-numeric-conversion, boost-range, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-tokenizer, boost-type-traits, boost-utility, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/date_time  
Description: Boost date_time module  
control: vcpkg/ports/boost-date-time/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-detail  
Version: 1.71.0  
Build-Depends: boost-compatibility, boost-config, boost-preprocessor, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/detail  
Description: Boost detail module  
control: vcpkg/ports/boost-detail/CONTROL

Source: boost-di  
Version: 1.1.0  
Homepage: https://github.com/boost-experimental/di  
Description: C++14 Dependency Injection Library.  
control: vcpkg/ports/boost-di/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-disjoint-sets  
Version: 1.71.0  
Build-Depends: boost-graph, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/disjoint_sets  
Description: Boost disjoint_sets module  
control: vcpkg/ports/boost-disjoint-sets/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-dll  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-filesystem (!uwp), boost-function, boost-integer, boost-move, boost-mpl, boost-predef, boost-smart-ptr, boost-spirit, boost-static-assert, boost-system, boost-throw-exception, boost-type-index, boost-type-traits, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/dll  
Description: Boost dll module  
control: vcpkg/ports/boost-dll/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-dynamic-bitset  
Version: 1.71.0  
Build-Depends: boost-serialization, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/dynamic_bitset  
Description: Boost dynamic_bitset module  
control: vcpkg/ports/boost-dynamic-bitset/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-endian  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-integer, boost-predef, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/endian  
Description: Boost endian module  
control: vcpkg/ports/boost-endian/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-exception  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-core, boost-modular-build-helper, boost-smart-ptr, boost-tuple, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/exception  
Description: Boost exception module  
control: vcpkg/ports/boost-exception/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-fiber  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-assert, boost-build, boost-config, boost-context (!uwp), boost-core, boost-detail, boost-filesystem (!uwp), boost-format, boost-intrusive, boost-modular-build-helper, boost-predef, boost-smart-ptr, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/fiber  
Description: Boost fiber module  
control: vcpkg/ports/boost-fiber/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-filesystem  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-core, boost-detail, boost-functional, boost-integer, boost-io, boost-iterator, boost-modular-build-helper, boost-smart-ptr, boost-system, boost-type-traits, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/filesystem  
Description: Boost filesystem module  
control: vcpkg/ports/boost-filesystem/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-flyweight  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-detail, boost-functional, boost-interprocess, boost-mpl, boost-multi-index, boost-parameter, boost-preprocessor, boost-serialization, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/flyweight  
Description: Boost flyweight module  
control: vcpkg/ports/boost-flyweight/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-foreach  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-detail, boost-iterator, boost-mpl, boost-range, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/foreach  
Description: Boost foreach module  
control: vcpkg/ports/boost-foreach/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-format  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-core, boost-detail, boost-optional, boost-smart-ptr, boost-throw-exception, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/format  
Description: Boost format module  
control: vcpkg/ports/boost-format/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-function  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-config, boost-core, boost-integer, boost-preprocessor, boost-throw-exception, boost-type-index, boost-typeof, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/function  
Description: Boost function module  
control: vcpkg/ports/boost-function/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-function-types  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-detail, boost-mpl, boost-preprocessor, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/function_types  
Description: Boost function_types module  
control: vcpkg/ports/boost-function-types/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-functional  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-iterator, boost-mpl, boost-preprocessor, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/functional  
Description: Boost functional module  
control: vcpkg/ports/boost-functional/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-fusion  
Version: 1.71.0  
Build-Depends: boost-config, boost-container-hash, boost-core, boost-detail, boost-function-types, boost-mpl, boost-preprocessor, boost-static-assert, boost-tuple, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/fusion  
Description: Boost fusion module  
control: vcpkg/ports/boost-fusion/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-geometry  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-array, boost-assert, boost-concept-check, boost-config, boost-container, boost-core, boost-detail, boost-function-types, boost-fusion, boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-move, boost-mpl, boost-multiprecision, boost-numeric-conversion, boost-polygon, boost-qvm, boost-range, boost-rational, boost-serialization, boost-smart-ptr, boost-static-assert, boost-thread, boost-throw-exception, boost-tokenizer, boost-tuple, boost-type-traits, boost-utility, boost-variant, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/geometry  
Description: Boost geometry module  
control: vcpkg/ports/boost-geometry/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-gil  
Version: 1.71.0  
Build-Depends: boost-assert, boost-concept-check, boost-config, boost-core, boost-filesystem (!uwp), boost-integer, boost-iterator, boost-mpl, boost-numeric-conversion, boost-type-traits, boost-utility, boost-variant, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/gil  
Description: Boost gil module  
control: vcpkg/ports/boost-gil/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-graph  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-any, boost-array, boost-assert, boost-bimap, boost-bind, boost-build, boost-compatibility, boost-concept-check, boost-config, boost-container-hash, boost-conversion, boost-core, boost-detail, boost-foreach, boost-function, boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-modular-build-helper, boost-move, boost-mpl, boost-multi-index, boost-optional, boost-parameter, boost-preprocessor, boost-property-map, boost-property-tree, boost-random, boost-range, boost-regex, boost-serialization, boost-smart-ptr, boost-spirit, boost-static-assert, boost-test (!uwp), boost-throw-exception, boost-tti, boost-tuple, boost-typeof, boost-type-traits, boost-unordered, boost-utility, boost-vcpkg-helpers, boost-xpressive  
Homepage: https://github.com/boostorg/graph  
Description: Boost graph module  
control: vcpkg/ports/boost-graph/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-graph-parallel  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-container-hash, boost-detail, boost-dynamic-bitset, boost-filesystem (!uwp), boost-foreach, boost-function, boost-graph, boost-iterator, boost-lexical-cast, boost-math, boost-mpl, boost-optional, boost-property-map, boost-random, boost-serialization, boost-smart-ptr, boost-static-assert, boost-tuple, boost-type-traits, boost-utility, boost-variant, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/graph_parallel  
Description: Boost graph_parallel module  
control: vcpkg/ports/boost-graph-parallel/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-hana  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-fusion, boost-mpl, boost-tuple, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/hana  
Description: Boost hana module  
control: vcpkg/ports/boost-hana/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-heap  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-bind, boost-concept-check, boost-integer, boost-intrusive, boost-iterator, boost-parameter, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/heap  
Description: Boost heap module  
control: vcpkg/ports/boost-heap/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-histogram  
Version: 1.71.0  
Build-Depends: boost-assert, boost-callable-traits, boost-config, boost-core, boost-mp11, boost-serialization, boost-throw-exception, boost-variant2, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/histogram  
Description: Boost histogram module  
control: vcpkg/ports/boost-histogram/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-hof  
Version: 1.71.0  
Build-Depends: boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/hof  
Description: Boost hof module  
control: vcpkg/ports/boost-hof/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-icl  
Version: 1.71.0  
Build-Depends: boost-assert, boost-concept-check, boost-config, boost-container, boost-date-time, boost-detail, boost-iterator, boost-move, boost-mpl, boost-range, boost-rational, boost-static-assert, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/icl  
Description: Boost icl module  
control: vcpkg/ports/boost-icl/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-integer  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-core, boost-detail, boost-static-assert, boost-throw-exception, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/integer  
Description: Boost integer module  
control: vcpkg/ports/boost-integer/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-interprocess  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-container, boost-core, boost-date-time, boost-detail, boost-integer, boost-intrusive, boost-move, boost-static-assert, boost-type-traits, boost-unordered, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/interprocess  
Description: Boost interprocess module  
control: vcpkg/ports/boost-interprocess/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-interval  
Version: 1.71.0  
Build-Depends: boost-compatibility, boost-config, boost-logic, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/interval  
Description: Boost interval module  
control: vcpkg/ports/boost-interval/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-intrusive  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-container-hash, boost-core, boost-integer, boost-move, boost-static-assert, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/intrusive  
Description: Boost intrusive module  
control: vcpkg/ports/boost-intrusive/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-io  
Version: 1.71.0  
Build-Depends: boost-detail, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/io  
Description: Boost io module  
control: vcpkg/ports/boost-io/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-iostreams  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-build, boost-config, boost-core, boost-detail, boost-function, boost-integer, boost-iterator, boost-modular-build-helper, boost-mpl, boost-numeric-conversion, boost-preprocessor, boost-range, boost-regex, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers, bzip2, liblzma, zlib, zstd  
Homepage: https://github.com/boostorg/iostreams  
Description: Boost iostreams module  
control: vcpkg/ports/boost-iostreams/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-iterator  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-concept-check, boost-config, boost-conversion, boost-core, boost-detail, boost-function-types, boost-fusion, boost-mpl, boost-optional, boost-smart-ptr, boost-static-assert, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/iterator  
Description: Boost iterator module  
control: vcpkg/ports/boost-iterator/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-lambda  
Version: 1.71.0  
Build-Depends: boost-bind, boost-config, boost-detail, boost-mpl, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/lambda  
Description: Boost lambda module  
control: vcpkg/ports/boost-lambda/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-lexical-cast  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-compatibility, boost-config, boost-container, boost-core, boost-detail, boost-integer, boost-numeric-conversion, boost-range, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/lexical_cast  
Description: Boost lexical_cast module  
control: vcpkg/ports/boost-lexical-cast/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-local-function  
Version: 1.71.0  
Build-Depends: boost-config, boost-mpl, boost-preprocessor, boost-scope-exit, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/local_function  
Description: Boost local_function module  
control: vcpkg/ports/boost-local-function/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-locale  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-function, boost-integer, boost-iterator, boost-modular-build-helper, boost-smart-ptr, boost-static-assert, boost-system, boost-thread, boost-type-traits, boost-unordered, boost-vcpkg-helpers, libiconv (!uwp&!windows)  
Homepage: https://github.com/boostorg/locale  
Description: Boost locale module  
  
Feature: icu  
Description: ICU backend for Boost.Locale  
Build-Depends: icu  
control: vcpkg/ports/boost-locale/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-lockfree  
Version: 1.71.0  
Build-Depends: boost-align, boost-array, boost-assert, boost-atomic, boost-config, boost-core, boost-integer, boost-mpl, boost-parameter, boost-predef, boost-static-assert, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/lockfree  
Description: Boost lockfree module  
control: vcpkg/ports/boost-lockfree/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-log  
Version: 1.71.0  
Build-Depends: boost-align, boost-array, boost-asio, boost-assert, boost-atomic, boost-bind, boost-build, boost-compatibility, boost-config, boost-container, boost-core, boost-date-time, boost-detail, boost-exception, boost-filesystem (!uwp), boost-function-types, boost-fusion, boost-integer, boost-interprocess, boost-intrusive, boost-io, boost-iterator, boost-lexical-cast, boost-locale (!uwp), boost-math, boost-modular-build-helper, boost-move, boost-mpl, boost-optional, boost-parameter, boost-phoenix, boost-predef, boost-preprocessor, boost-property-tree, boost-proto, boost-random, boost-range, boost-regex, boost-smart-ptr, boost-spirit, boost-static-assert, boost-system, boost-thread, boost-throw-exception, boost-type-index, boost-type-traits, boost-utility, boost-vcpkg-helpers, boost-winapi, boost-xpressive  
Homepage: https://github.com/boostorg/log  
Description: Boost log module  
control: vcpkg/ports/boost-log/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-logic  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-detail, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/logic  
Description: Boost logic module  
control: vcpkg/ports/boost-logic/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-math  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-atomic, boost-build, boost-compatibility, boost-concept-check, boost-config, boost-core, boost-detail, boost-fusion, boost-integer, boost-lambda, boost-lexical-cast, boost-modular-build-helper, boost-mp11, boost-mpl, boost-multiprecision, boost-predef, boost-range, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/math  
Description: Boost math module  
control: vcpkg/ports/boost-math/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-metaparse  
Version: 1.71.0  
Build-Depends: boost-config, boost-mpl, boost-predef, boost-preprocessor, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/metaparse  
Description: Boost metaparse module  
control: vcpkg/ports/boost-metaparse/CONTROL

Source: boost-modular-build-helper  
Version: 1.70.0-2  
control: vcpkg/ports/boost-modular-build-helper/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-move  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-integer, boost-static-assert, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/move  
Description: Boost move module  
control: vcpkg/ports/boost-move/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-mp11  
Version: 1.71.0  
Build-Depends: boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/mp11  
Description: Boost mp11 module  
control: vcpkg/ports/boost-mp11/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-mpi  
Version: 1.71.0-1  
Build-Depends: boost-assert, boost-build, boost-compatibility, boost-config, boost-core, boost-foreach, boost-function, boost-graph, boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-modular-build-helper, boost-mpl, boost-optional, boost-property-map, boost-python (windows), boost-serialization, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers, mpi  
Homepage: https://github.com/boostorg/mpi  
Description: Boost mpi module  
control: vcpkg/ports/boost-mpi/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-mpl  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-detail, boost-predef, boost-preprocessor, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/mpl  
Description: Boost mpl module  
control: vcpkg/ports/boost-mpl/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-msm  
Version: 1.71.0  
Build-Depends: boost-any, boost-assert, boost-bind, boost-circular-buffer, boost-config, boost-core, boost-detail, boost-function, boost-fusion, boost-mpl, boost-parameter, boost-phoenix, boost-preprocessor, boost-proto, boost-serialization, boost-tuple, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/msm  
Description: Boost msm module  
control: vcpkg/ports/boost-msm/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-multi-array  
Version: 1.71.0  
Build-Depends: boost-compatibility, boost-config, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/multi_array  
Description: Boost multi_array module  
control: vcpkg/ports/boost-multi-array/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-multi-index  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-compatibility, boost-config, boost-container-hash, boost-core, boost-detail, boost-foreach, boost-functional, boost-integer, boost-iterator, boost-move, boost-mpl, boost-preprocessor, boost-serialization, boost-static-assert, boost-throw-exception, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/multi_index  
Description: Boost multi_index module  
control: vcpkg/ports/boost-multi-index/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-multiprecision  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-config, boost-container-hash, boost-core, boost-functional, boost-integer, boost-lexical-cast, boost-mpl, boost-predef, boost-rational, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/multiprecision  
Description: Boost multiprecision module  
control: vcpkg/ports/boost-multiprecision/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-numeric-conversion  
Version: 1.71.0  
Build-Depends: boost-compatibility, boost-config, boost-conversion, boost-core, boost-detail, boost-integer, boost-preprocessor, boost-throw-exception, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/numeric_conversion  
Description: Boost numeric_conversion module  
control: vcpkg/ports/boost-numeric-conversion/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-odeint  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-bind, boost-compute, boost-config, boost-core, boost-function, boost-fusion, boost-iterator, boost-math, boost-mpl, boost-multi-array, boost-preprocessor, boost-range, boost-static-assert, boost-throw-exception, boost-type-traits, boost-units, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/odeint  
Description: Boost odeint module  
control: vcpkg/ports/boost-odeint/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-optional  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-detail, boost-move, boost-predef, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/optional  
Description: Boost optional module  
control: vcpkg/ports/boost-optional/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-outcome  
Version: 1.71.0  
Build-Depends: boost-config, boost-throw-exception, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/outcome  
Description: Boost outcome module  
control: vcpkg/ports/boost-outcome/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-parameter  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-function, boost-fusion, boost-mp11, boost-mpl, boost-optional, boost-preprocessor, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/parameter  
Description: Boost parameter module  
control: vcpkg/ports/boost-parameter/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-parameter-python  
Version: 1.71.0  
Build-Depends: boost-mpl, boost-parameter, boost-preprocessor, boost-python (windows), boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/parameter_python  
Description: Boost parameter_python module  
control: vcpkg/ports/boost-parameter-python/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-phoenix  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-config, boost-core, boost-detail, boost-function, boost-fusion, boost-mpl, boost-predef, boost-preprocessor, boost-proto, boost-range, boost-smart-ptr, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/phoenix  
Description: Boost phoenix module  
control: vcpkg/ports/boost-phoenix/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-poly-collection  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-detail, boost-iterator, boost-mp11, boost-mpl, boost-type-erasure (!arm), boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/poly_collection  
Description: Boost poly_collection module  
control: vcpkg/ports/boost-poly-collection/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-polygon  
Version: 1.71.0  
Build-Depends: boost-config, boost-integer, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/polygon  
Description: Boost polygon module  
control: vcpkg/ports/boost-polygon/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-pool  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-detail, boost-integer, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/pool  
Description: Boost pool module  
control: vcpkg/ports/boost-pool/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-predef  
Version: 1.71.0  
Build-Depends: boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/predef  
Description: Boost predef module  
control: vcpkg/ports/boost-predef/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-preprocessor  
Version: 1.71.0  
Build-Depends: boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/preprocessor  
Description: Boost preprocessor module  
control: vcpkg/ports/boost-preprocessor/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-process  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-asio, boost-config, boost-core, boost-filesystem (!uwp), boost-fusion, boost-iterator, boost-move, boost-optional, boost-system, boost-tokenizer, boost-type-index, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/process  
Description: Boost process module  
control: vcpkg/ports/boost-process/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-program-options  
Version: 1.71.0  
Build-Depends: boost-any, boost-bind, boost-build, boost-compatibility, boost-config, boost-core, boost-detail, boost-function, boost-iterator, boost-lexical-cast, boost-math, boost-modular-build-helper, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-tokenizer, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/program_options  
Description: Boost program_options module  
control: vcpkg/ports/boost-program-options/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-property-map  
Version: 1.71.0  
Build-Depends: boost-any, boost-assert, boost-bind, boost-concept-check, boost-config, boost-core, boost-detail, boost-function, boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-mpl, boost-multi-index, boost-optional, boost-serialization, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/property_map  
Description: Boost property_map module  
control: vcpkg/ports/boost-property-map/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-property-tree  
Version: 1.71.0  
Build-Depends: boost-any, boost-assert, boost-bind, boost-compatibility, boost-config, boost-core, boost-format, boost-iterator, boost-mpl, boost-multi-index, boost-optional, boost-range, boost-serialization, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/property_tree  
Description: Boost property_tree module  
control: vcpkg/ports/boost-property-tree/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-proto  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-detail, boost-fusion, boost-mpl, boost-preprocessor, boost-range, boost-static-assert, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/proto  
Description: Boost proto module  
control: vcpkg/ports/boost-proto/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-ptr-container  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-circular-buffer, boost-config, boost-core, boost-iterator, boost-mpl, boost-range, boost-serialization, boost-smart-ptr, boost-static-assert, boost-type-traits, boost-unordered, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/ptr_container  
Description: Boost ptr_container module  
control: vcpkg/ports/boost-ptr-container/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-python  
Version: 1.71.0-1  
Build-Depends: boost-bind, boost-compatibility, boost-config, boost-conversion, boost-core, boost-detail, boost-foreach, boost-function, boost-graph, boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-mpl, boost-numeric-conversion, boost-preprocessor, boost-property-map, boost-smart-ptr, boost-static-assert, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers, python3  
Homepage: https://github.com/boostorg/python  
Description: Boost python module  
control: vcpkg/ports/boost-python/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-qvm  
Version: 1.71.0  
Build-Depends: boost-assert, boost-exception, boost-static-assert, boost-throw-exception, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/qvm  
Description: Boost qvm module  
control: vcpkg/ports/boost-qvm/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-random  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-compatibility, boost-config, boost-core, boost-detail, boost-dynamic-bitset, boost-integer, boost-io, boost-math, boost-modular-build-helper, boost-mpl, boost-multiprecision, boost-range, boost-static-assert, boost-system, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/random  
Description: Boost random module  
control: vcpkg/ports/boost-random/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-range  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-concept-check, boost-config, boost-container-hash, boost-core, boost-detail, boost-integer, boost-iterator, boost-mpl, boost-optional, boost-preprocessor, boost-regex, boost-static-assert, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/range  
Description: Boost range module  
control: vcpkg/ports/boost-range/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-ratio  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-integer, boost-mpl, boost-rational, boost-static-assert, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/ratio  
Description: Boost ratio module  
control: vcpkg/ports/boost-ratio/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-rational  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-integer, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/rational  
Description: Boost rational module  
control: vcpkg/ports/boost-rational/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-regex  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-compatibility, boost-concept-check, boost-config, boost-container-hash, boost-core, boost-detail, boost-integer, boost-iterator, boost-modular-build-helper, boost-mpl, boost-predef, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/regex  
Description: Boost regex module  
  
Feature: icu  
Description: ICU backend for Boost.Regex  
Build-Depends: icu  
control: vcpkg/ports/boost-regex/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-safe-numerics  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-integer, boost-logic, boost-mp11, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/safe_numerics  
Description: Boost safe_numerics module  
control: vcpkg/ports/boost-safe-numerics/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-scope-exit  
Version: 1.71.0  
Build-Depends: boost-config, boost-detail, boost-function, boost-preprocessor, boost-typeof, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/scope_exit  
Description: Boost scope_exit module  
control: vcpkg/ports/boost-scope-exit/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-serialization  
Version: 1.71.0  
Build-Depends: boost-array, boost-assert, boost-build, boost-compatibility, boost-config, boost-core, boost-detail, boost-function, boost-integer, boost-io, boost-iterator, boost-modular-build-helper, boost-move, boost-mpl, boost-optional, boost-preprocessor, boost-smart-ptr, boost-spirit, boost-static-assert, boost-type-traits, boost-unordered, boost-utility, boost-variant, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/serialization  
Description: Boost serialization module  
control: vcpkg/ports/boost-serialization/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-signals  
Version: 1.68.0  
Build-Depends: boost-any, boost-build, boost-config, boost-core, boost-function, boost-iterator, boost-modular-build-helper, boost-optional, boost-smart-ptr, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/signals  
Description: Boost signals module  
control: vcpkg/ports/boost-signals/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-signals2  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-config, boost-core, boost-detail, boost-function, boost-iterator, boost-mpl, boost-optional, boost-parameter, boost-predef, boost-preprocessor, boost-smart-ptr, boost-throw-exception, boost-tuple, boost-type-traits, boost-utility, boost-variant, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/signals2  
Description: Boost signals2 module  
control: vcpkg/ports/boost-signals2/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-smart-ptr  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-detail, boost-integer, boost-move, boost-predef, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/smart_ptr  
Description: Boost smart_ptr module  
control: vcpkg/ports/boost-smart-ptr/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-sort  
Version: 1.71.0  
Build-Depends: boost-integer, boost-range, boost-serialization, boost-static-assert, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/sort  
Description: Boost sort module  
control: vcpkg/ports/boost-sort/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-spirit  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-array, boost-assert, boost-compatibility, boost-concept-check, boost-config, boost-core, boost-detail, boost-endian, boost-filesystem (!uwp), boost-foreach, boost-function, boost-function-types, boost-fusion, boost-integer, boost-io, boost-iostreams (!uwp), boost-iterator, boost-lexical-cast, boost-locale (!uwp), boost-math, boost-move, boost-mpl, boost-optional, boost-phoenix, boost-pool, boost-predef, boost-preprocessor, boost-proto, boost-range, boost-regex, boost-smart-ptr, boost-static-assert, boost-thread, boost-throw-exception, boost-tti, boost-typeof, boost-type-traits, boost-unordered, boost-utility, boost-variant, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/spirit  
Description: Boost spirit module  
control: vcpkg/ports/boost-spirit/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-stacktrace  
Version: 1.71.0  
Build-Depends: boost-array, boost-build, boost-config, boost-container-hash, boost-core, boost-modular-build-helper, boost-predef, boost-static-assert, boost-type-traits, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/stacktrace  
Description: Boost stacktrace module  
control: vcpkg/ports/boost-stacktrace/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-statechart  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-config, boost-conversion, boost-core, boost-detail, boost-function, boost-mpl, boost-smart-ptr, boost-static-assert, boost-thread, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/statechart  
Description: Boost statechart module  
control: vcpkg/ports/boost-statechart/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-static-assert  
Version: 1.71.0  
Build-Depends: boost-config, boost-detail, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/static_assert  
Description: Boost static_assert module  
control: vcpkg/ports/boost-static-assert/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-system  
Version: 1.71.0  
Build-Depends: boost-build, boost-config, boost-integer, boost-modular-build-helper, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/system  
Description: Boost system module  
control: vcpkg/ports/boost-system/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-test  
Version: 1.71.0-2  
Build-Depends: boost-algorithm, boost-assert, boost-bind, boost-build, boost-compatibility, boost-config, boost-core, boost-detail, boost-exception, boost-function, boost-integer, boost-io, boost-iterator, boost-modular-build-helper, boost-mpl, boost-numeric-conversion, boost-optional, boost-preprocessor, boost-smart-ptr, boost-static-assert, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/test  
Description: Boost test module  
control: vcpkg/ports/boost-test/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-thread  
Version: 1.71.0  
Build-Depends: boost-algorithm, boost-assert, boost-atomic, boost-bind, boost-build, boost-chrono, boost-concept-check, boost-config, boost-container, boost-container-hash, boost-core, boost-date-time, boost-detail, boost-exception, boost-function, boost-integer, boost-intrusive, boost-io, boost-lexical-cast, boost-math, boost-modular-build-helper, boost-move, boost-mpl, boost-optional, boost-predef, boost-preprocessor, boost-smart-ptr, boost-static-assert, boost-system, boost-throw-exception, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/thread  
Description: Boost thread module  
control: vcpkg/ports/boost-thread/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-throw-exception  
Version: 1.71.0  
Build-Depends: boost-config, boost-detail, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/throw_exception  
Description: Boost throw_exception module  
control: vcpkg/ports/boost-throw-exception/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-timer  
Version: 1.71.0  
Build-Depends: boost-build, boost-chrono, boost-compatibility, boost-config, boost-core, boost-integer, boost-io, boost-modular-build-helper, boost-predef, boost-system, boost-throw-exception, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/timer  
Description: Boost timer module  
control: vcpkg/ports/boost-timer/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-tokenizer  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-detail, boost-iterator, boost-mpl, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/tokenizer  
Description: Boost tokenizer module  
control: vcpkg/ports/boost-tokenizer/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-tti  
Version: 1.71.0  
Build-Depends: boost-config, boost-detail, boost-function-types, boost-mpl, boost-preprocessor, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/tti  
Description: Boost tti module  
control: vcpkg/ports/boost-tti/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-tuple  
Version: 1.71.0  
Build-Depends: boost-config, boost-core, boost-static-assert, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/tuple  
Description: Boost tuple module  
control: vcpkg/ports/boost-tuple/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-type-erasure  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-config, boost-detail, boost-fusion, boost-iterator, boost-modular-build-helper, boost-mp11, boost-mpl, boost-preprocessor, boost-smart-ptr, boost-thread, boost-throw-exception, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers, boost-vmd  
Homepage: https://github.com/boostorg/type_erasure  
Description: Boost type_erasure module  
control: vcpkg/ports/boost-type-erasure/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-type-index  
Version: 1.71.0  
Build-Depends: boost-config, boost-container-hash, boost-core, boost-preprocessor, boost-smart-ptr, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/type_index  
Description: Boost type_index module  
control: vcpkg/ports/boost-type-index/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-type-traits  
Version: 1.71.0  
Build-Depends: boost-config, boost-detail, boost-static-assert, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/type_traits  
Description: Boost type_traits module  
control: vcpkg/ports/boost-type-traits/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-typeof  
Version: 1.71.0  
Build-Depends: boost-config, boost-preprocessor, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/typeof  
Description: Boost typeof module  
control: vcpkg/ports/boost-typeof/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-ublas  
Version: 1.71.0  
Build-Depends: boost-compute, boost-concept-check, boost-config, boost-core, boost-iterator, boost-mpl, boost-range, boost-serialization, boost-smart-ptr, boost-static-assert, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/ublas  
Description: Boost ublas module  
control: vcpkg/ports/boost-ublas/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-units  
Version: 1.71.0  
Build-Depends: boost-assert, boost-config, boost-core, boost-integer, boost-io, boost-lambda, boost-math, boost-mpl, boost-preprocessor, boost-serialization, boost-static-assert, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/units  
Description: Boost units module  
control: vcpkg/ports/boost-units/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-unordered  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-container, boost-container-hash, boost-core, boost-detail, boost-functional, boost-move, boost-predef, boost-preprocessor, boost-smart-ptr, boost-throw-exception, boost-tuple, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/unordered  
Description: Boost unordered module  
control: vcpkg/ports/boost-unordered/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-utility  
Version: 1.71.0  
Build-Depends: boost-config, boost-container-hash, boost-core, boost-detail, boost-integer, boost-preprocessor, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/utility  
Description: Boost utility module  
control: vcpkg/ports/boost-utility/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-uuid  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-container-hash, boost-core, boost-integer, boost-io, boost-move, boost-numeric-conversion, boost-predef, boost-random, boost-serialization, boost-static-assert, boost-throw-exception, boost-tti, boost-type-traits, boost-vcpkg-helpers, boost-winapi  
Homepage: https://github.com/boostorg/uuid  
Description: Boost uuid module  
control: vcpkg/ports/boost-uuid/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-variant  
Version: 1.71.0  
Build-Depends: boost-assert, boost-bind, boost-config, boost-core, boost-detail, boost-functional, boost-integer, boost-move, boost-mpl, boost-preprocessor, boost-static-assert, boost-throw-exception, boost-type-index, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/variant  
Description: Boost variant module  
control: vcpkg/ports/boost-variant/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-variant2  
Version: 1.71.0  
Build-Depends: boost-config, boost-detail, boost-mp11, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/variant2  
Description: Boost variant2 module  
control: vcpkg/ports/boost-variant2/CONTROL

Source: boost-vcpkg-helpers  
Version: 6  
Description: a set of vcpkg-internal scripts used to modularize boost  
control: vcpkg/ports/boost-vcpkg-helpers/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-vmd  
Version: 1.71.0  
Build-Depends: boost-preprocessor, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/vmd  
Description: Boost vmd module  
control: vcpkg/ports/boost-vmd/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-wave  
Version: 1.71.0  
Build-Depends: boost-assert, boost-build, boost-concept-check, boost-config, boost-core, boost-detail, boost-filesystem (!uwp), boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-modular-build-helper, boost-mpl, boost-multi-index, boost-pool, boost-preprocessor, boost-serialization, boost-smart-ptr, boost-spirit, boost-static-assert, boost-throw-exception, boost-type-traits, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/wave  
Description: Boost wave module  
control: vcpkg/ports/boost-wave/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-winapi  
Version: 1.71.0  
Build-Depends: boost-config, boost-predef, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/winapi  
Description: Boost winapi module  
control: vcpkg/ports/boost-winapi/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-xpressive  
Version: 1.71.0  
Build-Depends: boost-assert, boost-compatibility, boost-config, boost-conversion, boost-core, boost-detail, boost-exception, boost-fusion, boost-integer, boost-iterator, boost-lexical-cast, boost-math, boost-mpl, boost-numeric-conversion, boost-optional, boost-preprocessor, boost-proto, boost-range, boost-smart-ptr, boost-spirit, boost-static-assert, boost-throw-exception, boost-typeof, boost-type-traits, boost-utility, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/xpressive  
Description: Boost xpressive module  
control: vcpkg/ports/boost-xpressive/CONTROL

# Automatically generated by boost-vcpkg-helpers/generate-ports.ps1  
Source: boost-yap  
Version: 1.71.0  
Build-Depends: boost-hana, boost-preprocessor, boost-type-index, boost-vcpkg-helpers  
Homepage: https://github.com/boostorg/yap  
Description: Boost yap module  
control: vcpkg/ports/boost-yap/CONTROL

Source: botan  
Version: 2.11.0  
Homepage: https://botan.randombit.net  
Description: A cryptography library written in C++11  
control: vcpkg/ports/botan/CONTROL

Source: box2d  
Version: 2.3.1-374664b-2  
Description: An open source C++ engine for simulating rigid bodies in 2D.  
Homepage: https://box2d.org  
control: vcpkg/ports/box2d/CONTROL

Source: breakpad  
Version: 2019-07-11-1  
Build-Depends: libdisasm  
Homepage: https://github.com/google/breakpad  
Description: a set of client and server components which implement a crash-reporting system.  
control: vcpkg/ports/breakpad/CONTROL

Source: brigand  
Version: 1.3.0  
Homepage: https://github.com/edouarda/brigand  
Description: Brigand is a light-weight, fully functional, instant-compile time C++ 11 meta-programming library.  
Build-Depends: boost  
  
control: vcpkg/ports/brigand/CONTROL

Source: brotli  
Version: 1.0.7  
Homepage: https://github.com/google/brotli  
Description: a generic-purpose lossless compression algorithm that compresses data using a combination of a modern variant of the LZ77 algorithm, Huffman coding and 2nd order context modeling.  
control: vcpkg/ports/brotli/CONTROL

Source: brunocodutra-metal  
Version: v2.0.1-1  
Description: A single header C++11 library designed to make you love template metaprogramming  
control: vcpkg/ports/brunocodutra-metal/CONTROL

Source: brynet  
Version: 1.0.3  
Homepage: https://github.com/IronsDu/brynet  
Description: A C++ cross platform high performance tcp network library, and support SSL/HTTP/Websocket.  
Build-Depends: openssl  
control: vcpkg/ports/brynet/CONTROL

Source: bullet3  
Version: 2.88-1  
Homepage: https://github.com/bulletphysics/bullet3  
Description: Bullet Physics is a professional collision detection, rigid body, and soft body dynamics library  
  
Feature: multithreading  
Description: Multithreading funcitonality for bullet3  
control: vcpkg/ports/bullet3/CONTROL

Source: butteraugli  
Version: 2019-05-08  
Homepage: https://github.com/google/butteraugli  
Description: butteraugli estimates the psychovisual difference between two images  
Build-Depends: libpng, libjpeg-turbo  
control: vcpkg/ports/butteraugli/CONTROL

Source: byte-lite  
Version: 0.2.0  
Description: A C++17-like byte type for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/byte-lite/CONTROL

Source: bzip2  
Version: 1.0.6-4  
Homepage: http://www.bzip.org/  
Description: High-quality data compressor.  
control: vcpkg/ports/bzip2/CONTROL

Source: c-ares  
Version: 2019-5-2-1  
Homepage: https://github.com/c-ares/c-ares  
Description: A C library for asynchronous DNS requests  
control: vcpkg/ports/c-ares/CONTROL

Source: caf  
Version: 0.16.3  
Build-Depends: openssl  
Description: an open source C++11 actor model implementation featuring lightweight & fast actor implementations, pattern matching for messages, network transparent messaging, and more.  
control: vcpkg/ports/caf/CONTROL

Source: caffe2  
Version: 0.8.1-3  
Build-Depends: lmdb, gflags, glog, eigen3, protobuf  
Homepage: https://github.com/caffe2/caffe2  
Description: Caffe2 is a lightweight, modular, and scalable deep learning framework.  
control: vcpkg/ports/caffe2/CONTROL

Source: cairo  
Version: 1.16.0-2  
Homepage: https://cairographics.org  
Description: Cairo is a 2D graphics library with support for multiple output devices. Currently supported output targets include the X Window System (via both Xlib and XCB), Quartz, Win32, image buffers, PostScript, PDF, and SVG file output. Experimental backends include OpenGL, BeOS, OS/2, and DirectFB.  
Build-Depends: zlib, libpng, pixman, glib, freetype, fontconfig  
  
Feature: x11  
Description: build with x11 support  
control: vcpkg/ports/cairo/CONTROL

Source: cairomm  
Version: 1.15.3-3  
Homepage: https://www.cairographics.org  
Description: A C++ wrapper for the cairo graphics library  
Build-Depends: cairo, libsigcpp  
control: vcpkg/ports/cairomm/CONTROL

Source: capnproto  
Version: 0.7.0-3  
Description: Data interchange format and capability-based RPC system  
Homepage: https://capnproto.org/  
Build-Depends: zlib  
control: vcpkg/ports/capnproto/CONTROL

Source: capstone  
Version: 4.0.1-120373dc  
Homepage: https://github.com/aquynh/capstone  
Description: Multi-architecture disassembly framework  
  
Feature: arm  
Description: Capstone disassembly support for ARM  
  
Feature: arm64  
Description: Capstone disassembly support for ARM64  
  
Feature: evm  
Description: Capstone disassembly support for EVM  
  
Feature: m680x  
Description: Capstone disassembly support for M680X  
  
Feature: m68k  
Description: Capstone disassembly support for M68k  
  
Feature: mips  
Description: Capstone disassembly support for MIPS  
  
Feature: ppc  
Description: Capstone disassembly support for PowerPC  
  
Feature: sparc  
Description: Capstone disassembly support for SPARC  
  
Feature: sysz  
Description: Capstone disassembly support for SysZ  
  
Feature: tms320c64x  
Description: Capstone disassembly support for TMS320C64X  
  
Feature: x86  
Description: Capstone disassembly support for x86  
  
Feature: x86_reduce  
Description: Capstone disassembly support for x86 without support for less used instructions  
  
Feature: xcore  
Description: Capstone disassembly support for XCore  
  
Feature: diet  
Description: Build Capstone in diet mode (reduced features for smaller size)  
  
Feature: osxkernel  
Description: Support for emedding Capstone into OSX Kernel extensions  
control: vcpkg/ports/capstone/CONTROL

Source: cartographer  
Version: 1.0.0-1  
Build-Depends: ceres[suitesparse], gflags, glog, lua, cairo, boost-iostreams, gtest, protobuf  
Homepage: https://github.com/googlecartographer/cartographer  
Description: Google 2D & 3D SLAM package  
control: vcpkg/ports/cartographer/CONTROL

Source: casclib  
Version: 1.50b-1  
Build-Depends: zlib  
Description: An open-source implementation of library for reading CASC storage from Blizzard games since 2014  
control: vcpkg/ports/casclib/CONTROL

Source: catch  
Version: alias  
Build-Depends: catch2  
Description: Deprecated alias for Catch2 unit testing framework  
control: vcpkg/ports/catch/CONTROL

Source: catch-classic  
Version: 1.12.2  
Homepage: https://github.com/catchorg/Catch2  
Description: A modern, header-only test framework for unit tests  
 This is specifically the legacy 1.x branch provided for compatibility  
 with older compilers.  
control: vcpkg/ports/catch-classic/CONTROL

Source: catch2  
Version: 2.9.2  
Description: A modern, header-only test framework for unit testing.  
Homepage: https://github.com/catchorg/Catch2  
control: vcpkg/ports/catch2/CONTROL

Source: cccapstone  
Version: 9b4128ee1153e78288a1b5433e2c06a0d47a4c4e-1  
Homepage: https://github.com/zer0mem/cccapstone  
Description: c++ bindings for capstone disasembly framework  
Build-Depends: capstone  
control: vcpkg/ports/cccapstone/CONTROL

Source: ccd  
Version: 2.1-1  
Homepage: https://github.com/danfis/libccd  
Description: Library for collision detection between two convex shapes  
control: vcpkg/ports/ccd/CONTROL

Source: ccfits  
Version: 2.5-3  
Homepage: https://heasarc.gsfc.nasa.gov/fitsio/ccfits  
Description: CCfits is an object oriented interface to the cfitsio library. It is designed to make the capabilities of cfitsio available to programmers working in C++.  
Build-Depends: cfitsio  
control: vcpkg/ports/ccfits/CONTROL

Source: cctz  
Version: 2.3-2  
Homepage: https://github.com/google/cctz  
Build-Depends: benchmark  
Description: two libraries that cooperate with <chrono> to give C++ programmers all the necessary tools for computing with dates, times, and time zones in a simple and correct manner.  
control: vcpkg/ports/cctz/CONTROL

Source: celero  
Version: 2.5.0-1  
Homepage: https://github.com/DigitalInBlue/Celero  
Description: Celero is a modern cross-platform (Windows, Linux, MacOS) Microbenchmarking library for C++.  
control: vcpkg/ports/celero/CONTROL

Source: cello  
Version: 2019-07-23  
Description: Higher level programming in C  
Homepage: http://libcello.org/  
control: vcpkg/ports/cello/CONTROL

Source: cereal  
Version: 1.2.2-2  
Homepage: https://github.com/USCiLab/cereal  
Description: a header-only C++11 serialization library (built in support for binary, XML and JSon)  
control: vcpkg/ports/cereal/CONTROL

Source: ceres  
Version: 1.14.0-6  
Build-Depends: glog, eigen3  
Homepage: https://github.com/ceres-solver/ceres-solver  
Description: non-linear optimization package  
  
Feature: lapack  
Build-Depends: clapack (!osx)  
Description: Use Lapack in Ceres  
  
Feature: suitesparse  
Build-Depends: ceres[lapack], suitesparse[core]  
Description: SuiteSparse support for Ceres  
  
Feature: cxsparse  
Build-Depends: suitesparse[core]  
Description: CXSparse support for Ceres  
  
Feature: eigensparse  
Description: Use of Eigen as a sparse linear algebra library in Ceres  
  
Feature: tools  
Build-Depends: gflags  
Description: Ceres tools  
control: vcpkg/ports/ceres/CONTROL

Source: cfitsio  
Version: 3.410-2  
Homepage: https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c  
Description: Library of C and Fortran subroutines for reading and writing data files in FITS (Flexible Image Transport System) data format  
control: vcpkg/ports/cfitsio/CONTROL

Source: cgal  
Version: 4.14-3  
Build-Depends: mpfr, mpir, zlib, boost-format, boost-container, boost-iterator, boost-variant, boost-any, boost-unordered, boost-random, boost-foreach, boost-graph, boost-heap, boost-logic, boost-multiprecision  
Homepage: https://github.com/CGAL/cgal  
Description: The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry.  
  
Feature: qt  
Build-Depends: qt5-base, qt5-3d, qt5-svg, qt5-xmlpatterns, qt5-script, eigen3  
Description: Qt GUI support for CGAL  
control: vcpkg/ports/cgal/CONTROL

Source: cgicc  
Version: 3.2.19-3  
Homepage: https://www.gnu.org/software/cgicc/  
Description: GNU Cgicc is an ANSI C++ compliant class library that greatly simplifies the creation of CGI applications for the World Wide Web  
control: vcpkg/ports/cgicc/CONTROL

Source: cgl  
Version: 0.60.2-1  
Homepage: https://github.com/coin-or/Cgl  
Description: The COIN-OR Cut Generation Library (Cgl) is a collection of cut generators that can be used with other COIN-OR packages that make use of cuts, such as, among others, the linear solver Clp or the mixed integer linear programming solvers Cbc or BCP.  
Build-Depends: coinutils, osi, clp  
control: vcpkg/ports/cgl/CONTROL

Source: cgltf  
Version: 1.3  
Description: Single-file glTF 2.0 parser written in C99  
control: vcpkg/ports/cgltf/CONTROL

Source: chaiscript  
Version: 6.1.0-1  
Homepage: https://github.com/ChaiScript/ChaiScript  
Description: Embedded Scripting Language Designed for C++  
control: vcpkg/ports/chaiscript/CONTROL

Source: chakracore  
Version: 1.11.13  
Homepage: https://github.com/Microsoft/ChakraCore  
Description: Core part of the Chakra Javascript engine  
control: vcpkg/ports/chakracore/CONTROL

Source: charls  
Version: 2.0.0-2  
Homepage: https://github.com/team-charls/charls  
Description: CharLS, a C++ JPEG-LS library implementation.  
control: vcpkg/ports/charls/CONTROL

Source: chartdir  
Version: 6.3.1-1  
Homepage: https://www.advsofteng.com/  
Description: ChartDirector is a powerful chart component for creating professional looking charts for web and windows applications.  
control: vcpkg/ports/chartdir/CONTROL

Source: check  
Version: 0.12.0-2  
Description: A unit testing framework for C  
control: vcpkg/ports/check/CONTROL

Source: chipmunk  
Version: 7.0.3  
Homepage: https://github.com/slembcke/Chipmunk2D  
Description: A fast and lightweight 2D game physics library.  
control: vcpkg/ports/chipmunk/CONTROL

Source: chmlib  
Version: 0.40-3  
Homepage: https://www.jedrea.com/chmlib/  
Description: CHMLIB is a library for dealing with Microsoft ITSS/CHM format files. Right now, it is a very simple library, but sufficient for dealing with all of the .chm files I've come across. Due to the fairly well-designed indexing built into this particular file format, even a small library is able to gain reasonably good performance indexing into ITSS archives.  
control: vcpkg/ports/chmlib/CONTROL

Source: cimg  
Version: 2.6.2  
Homepage: https://github.com/dtschump/CImg  
Description: The CImg Library is a small, open-source, and modern C++ toolkit for image processing  
control: vcpkg/ports/cimg/CONTROL

Source: cityhash  
Version: 2013-01-08  
Homepage: https://github.com/google/cityhash  
Description: CityHash, a family of hash functions for strings.  
control: vcpkg/ports/cityhash/CONTROL

Source: civetweb  
Version: 2019-07-05  
Description: Easy to use, powerful, C/C++ embeddable web server.  
control: vcpkg/ports/civetweb/CONTROL

Source: cjson  
Version: 1.7.12  
Description: Ultralightweight JSON parser in ANSI C  
  
Feature: utils  
Description: Enable building the cJSON_Utils library  
control: vcpkg/ports/cjson/CONTROL

Source: clapack  
Version: 3.2.1-12  
Homepage: https://www.netlib.org/clapack  
Description: CLAPACK (f2c'ed version of LAPACK)  
Build-Depends: openblas (!osx)  
control: vcpkg/ports/clapack/CONTROL

Source: clara  
Version: 1.1.5  
Homepage: https://github.com/philsquared/Clara  
Description: A simple to use command line parser for C++  
control: vcpkg/ports/clara/CONTROL

Source: clblas  
Version: 2.12-2  
Build-Depends: opencl  
Description: clBLAS is an OpenCL 1.2 accelerated BLAS (Basic Linear Algebra Subsystem) library.  
control: vcpkg/ports/clblas/CONTROL

Source: clblast  
Version: 1.5.0  
Build-Depends: opencl  
Description: A modern, lightweight, performant and tunable OpenCL BLAS library written in C++11.  
control: vcpkg/ports/clblast/CONTROL

Source: clfft  
Version: 2.12.2-1  
Build-Depends: opencl  
Homepage: https://github.com/clMathLibraries/clFFT  
Description: clFFT is an OpenCL 1.2 accelerated Fast Fourier Transform library.  
control: vcpkg/ports/clfft/CONTROL

Source: cli  
Version: 1.1.1  
Description: A library for interactive command line interfaces in modern C++  
Build-Depends: boost-asio  
control: vcpkg/ports/cli/CONTROL

Source: cli11  
Version: 1.8.0  
Description: CLI11 is a command line parser for C++11 and beyond that provides a rich feature set with a simple and intuitive interface.  
Homepage: https://github.com/CLIUtils/CLI11  
control: vcpkg/ports/cli11/CONTROL

Source: clickhouse-cpp  
Version: 2019-05-22  
Build-Depends: lz4, cityhash  
Homepage: https://github.com/artpaul/clickhouse-cpp  
Description: C++ client for Yandex ClickHouse.  
control: vcpkg/ports/clickhouse-cpp/CONTROL

Source: clipp  
Version: 2019-04-30  
Description: command line interfaces for modern C++  
control: vcpkg/ports/clipp/CONTROL

Source: clockutils  
Version: 1.1.1-3651f232c27074c4ceead169e223edf5f00247c5-3  
Homepage: https://github.com/ClockworkOrigins/clockUtils  
Description: A lightweight c++ library for commonly needed tasks. Optimized for simplicity and speed.  
control: vcpkg/ports/clockutils/CONTROL

Source: clp  
Version: 1.17.3  
Description: Clp (Coin-or linear programming) is an open-source linear programming solver written in C++. It is primarily meant to be used as a callable library, but a basic, stand-alone executable version is also available.  
Build-Depends: coinutils, osi  
control: vcpkg/ports/clp/CONTROL

Source: clue  
Version: 1.0.0-alpha.7  
Homepage: https://github.com/martinmoene/clue  
Description: clue is a C++03 header-only library to log messages with a severity and optional module identifier.   
  
Feature: test  
Description: Build test  
control: vcpkg/ports/clue/CONTROL

Source: cmark  
Version: 0.29.0  
Description: CommonMark parsing and rendering library  
control: vcpkg/ports/cmark/CONTROL

Source: cmcstl2  
Version: 2019-07-20  
Description: An implementation of C++ Extensions for Ranges  
Homepage: https://github.com/CaseyCarter/cmcstl2  
control: vcpkg/ports/cmcstl2/CONTROL

Source: cmocka  
Version: 1.1.5-1  
Description: An elegant unit testing framework for C with support for mock objects  
control: vcpkg/ports/cmocka/CONTROL

Source: cnl  
Version: 2019-06-23  
Description: A Compositional Numeric Library for C++  
control: vcpkg/ports/cnl/CONTROL

Source: coinutils  
Version: 2.11.2-2  
Description: CoinUtils (Coin-or Utilities) is an open-source collection of classes and functions that are generally useful to more than one COIN-OR project  
control: vcpkg/ports/coinutils/CONTROL

Source: collada-dom  
Version: 2.5.0-2  
Description: The COLLADA Document Object Model (DOM) is an application programming interface (API) that provides a C++ object representation of a COLLADA XML instance document.  
Build-Depends: zlib, libxml2, minizip, pcre, uriparser, boost-filesystem, boost-system  
control: vcpkg/ports/collada-dom/CONTROL

Source: concurrentqueue  
Version: 1.0.0-beta-dea078c  
Description: A fast multi-producer, multi-consumer lock-free concurrent queue for C++11  
control: vcpkg/ports/concurrentqueue/CONTROL

Source: console-bridge  
Version: 0.4.3-1  
Homepage: https://github.com/ros/console_bridge  
Description: a ROS-independent package for logging that seamlessly pipes into rosconsole/rosout for ROS-dependent packages.  
control: vcpkg/ports/console-bridge/CONTROL

Source: constexpr  
Version: 1.0-1  
Homepage: https://github.com/elbeno/constexpr  
Description: Small MIT License Library of general stdlib functions written as C++11 constexpr functions.  
control: vcpkg/ports/constexpr/CONTROL

Source: coolprop  
Version: 6.1.0-4  
Homepage: https://github.com/CoolProp/CoolProp  
Description: Thermophysical properties for the masses  
Build-Depends: catch, eigen3, pybind11, if97, fmt, rapidjson, msgpack, refprop-headers  
control: vcpkg/ports/coolprop/CONTROL

Source: coroutine  
Version: 1.4.3  
Build-Depends: ms-gsl  
Description: C++ coroutine helper/example library  
control: vcpkg/ports/coroutine/CONTROL

Source: corrade  
Version: 2019.01-1  
Description: C++11/C++14 multiplatform utility library  
Homepage: https://magnum.graphics/corrade/  
Default-Features: interconnect, pluginmanager, testsuite, utility  
  
Feature: interconnect  
Description: Interconnect library  
Build-Depends: corrade[utility]  
  
Feature: pluginmanager  
Description: PluginManager library  
Build-Depends: corrade[utility]  
  
Feature: testsuite  
Description: TestSuite library  
Build-Depends: corrade[utility]  
  
Feature: utility  
Description: Utility library  
control: vcpkg/ports/corrade/CONTROL

Source: cpp-base64  
Version: 2019-06-19  
Homepage: https://github.com/ReneNyffenegger/cpp-base64  
Description: Base64 encoding and decoding with c++.  
control: vcpkg/ports/cpp-base64/CONTROL

Source: cpp-httplib  
Version: 0.2.4  
Homepage: https://github.com/yhirose/cpp-httplib  
Description: A single file C++11 header-only HTTP/HTTPS server and client library  
control: vcpkg/ports/cpp-httplib/CONTROL

Source: cpp-netlib  
Version: 0.13.0-2  
Build-Depends: boost  
Description: A collection of network-related routines/implementations geared towards providing a robust cross-platform networking library  
control: vcpkg/ports/cpp-netlib/CONTROL

Source: cpp-peglib  
Version: 0.1.0  
Description: C++11 header-only PEG (Parsing Expression Grammars) library.   
control: vcpkg/ports/cpp-peglib/CONTROL

Source: cpp-redis  
Version: 4.3.1-2  
Build-Depends: tacopie  
Homepage: https://github.com/cpp-redis/cpp_redis  
Description: cpp-redis is a C++11 Asynchronous Multi-Platform Lightweight Redis Client, with support for synchronous operations and pipelining.  
control: vcpkg/ports/cpp-redis/CONTROL

Source: cpp-taskflow  
Version: 2.2.0  
Description: Fast Parallel Tasking Programming Library using Modern C++.  
control: vcpkg/ports/cpp-taskflow/CONTROL

Source: cppcms  
Version: 1.2.1  
Homepage: https://github.com/artyom-beilis/cppcms  
Description: CppCMS is a Free High Performance Web Development Framework (not a CMS) aimed at Rapid Web Application Development  
Build-Depends: icu, pcre, openssl, zlib  
control: vcpkg/ports/cppcms/CONTROL

Source: cppcodec  
Version: 0.2  
Description: Header-only C++11 library to encode/decode base64, base64url, base32, base32hex and hex (a.k.a. base16) as specified in RFC 4648, plus Crockford's base32.  
control: vcpkg/ports/cppcodec/CONTROL

Source: cppfs  
Version: 1.2.0-1  
Description: Cross-platform C++ file system library supporting multiple backends  
  
Feature: ssh  
Description: SSH backend for cppfs  
Build-Depends: libssh2,openssl,zlib  
control: vcpkg/ports/cppfs/CONTROL

Source: cppgraphqlgen  
Version: 3.0.2  
Build-Depends: boost-filesystem (!uwp&!windows), boost-program-options, pegtl, rapidjson  
Description: C++ GraphQL schema service generator  
control: vcpkg/ports/cppgraphqlgen/CONTROL

Source: cppitertools  
Version: 2019-04-14-2  
Description: Range-based for loop add-ons inspired by the Python builtins and itertools library  
Build-Depends: boost-optional  
control: vcpkg/ports/cppitertools/CONTROL

Source: cppkafka  
Version: 0.3.1-1  
Homepage: https://github.com/mfontanini/cppkafka  
Description: cppkafka allows C++ applications to consume and produce messages using the Apache Kafka protocol. The library is built on top of librdkafka, and provides a high level API that uses modern C++ features to make it easier to write code while keeping the wrapper's performance overhead to a minimum.  
Build-Depends: boost-program-options, librdkafka  
control: vcpkg/ports/cppkafka/CONTROL

Source: cppmicroservices  
Version: 4.0.0-pre1  
Description: An OSGi-like C++ dynamic module system and service registry  
control: vcpkg/ports/cppmicroservices/CONTROL

Source: cpprestsdk  
Version: 2.10.14-1  
Build-Depends: openssl (!uwp&!windows), boost-system (!uwp&!windows),   
  boost-date-time (!uwp&!windows), boost-regex (!uwp&!windows), boost-thread (!uwp&!windows),  
  boost-filesystem (!uwp&!windows), boost-random (!uwp&!windows), boost-chrono (!uwp&!windows),   
  boost-asio (!uwp&!windows)  
Homepage: https://github.com/Microsoft/cpprestsdk  
Description: C++11 JSON, REST, and OAuth library  
  The C++ REST SDK is a Microsoft project for cloud-based client-server communication in native code using a modern asynchronous C++ API design. This project aims to help C++ developers connect to and interact with services.  
Default-Features: default-features  
  
Feature: default-features  
Build-Depends: cpprestsdk[brotli] (windows), cpprestsdk[core,compression,websockets]  
Description: Features installed by default  
  
Feature: compression  
Build-Depends: zlib  
Description: HTTP Compression support  
  
Feature: websockets  
Build-Depends: cpprestsdk[core,compression], websocketpp (!uwp), openssl (!uwp), boost-system (!uwp), boost-date-time (!uwp), boost-regex (!uwp)  
Description: Websockets support  
  
Feature: brotli  
Build-Depends: cpprestsdk[core,compression], brotli  
Description: Brotli compression support  
control: vcpkg/ports/cpprestsdk/CONTROL

Source: cpptoml  
Version: v0.1.1  
Description: A header-only library for parsing TOML configuration files.  
control: vcpkg/ports/cpptoml/CONTROL

Source: cppunit  
Version: 1.14.0  
Description: CppUnit is the C++ port of the famous JUnit framework for unit testing. Test output is in XML for automatic testing and GUI based for supervised tests.  
control: vcpkg/ports/cppunit/CONTROL

Source: cpputest  
Version: 2019-9-16  
Homepage: https://github.com/cpputest/cpputest  
Description: CppUTest unit testing and mocking framework for C/C++.  
control: vcpkg/ports/cpputest/CONTROL

Source: cppwinrt  
Version: fall_2017_creators_update_for_vs_15.3-2  
Homepage: https://github.com/Microsoft/cppwinrt  
Description: C++/WinRT is a standard C++ language projection for the Windows Runtime.  
control: vcpkg/ports/cppwinrt/CONTROL

Source: cppzmq  
Version: 4.4.1  
Build-Depends: zeromq  
Homepage: https://github.com/zeromq/cppzmq  
Description: lightweight messaging kernel, C++ bindings  
control: vcpkg/ports/cppzmq/CONTROL

Source: cpr  
Version: 1.3.0-7  
Homepage: https://github.com/whoshuu/cpr  
Description: C++ Requests is a simple wrapper around libcurl inspired by the excellent Python Requests project.  
Build-Depends: curl[core]  
control: vcpkg/ports/cpr/CONTROL

Source: cpuinfo  
Version: 2019-07-28  
Description: CPU INFOrmation library (x86/x86-64/ARM/ARM64, Linux/Windows/Android/macOS/iOS)  
Homepage: https://github.com/pytorch/cpuinfo  
  
Feature: tools  
Description: Build cpuinfo command-line tools  
control: vcpkg/ports/cpuinfo/CONTROL

Source: crc32c  
Version: 1.1.0  
Homepage: https://github.com/google/crc32c  
Description: CRC32C implementation with support for CPU-specific acceleration instructions.  
control: vcpkg/ports/crc32c/CONTROL

Source: crfsuite  
Version: 2019-07-21  
Homepage: http://www.chokkan.org/software/crfsuite/  
Build-Depends: liblbfgs  
Description:  CRFSuite is an implementation of Conditional Random Fields (CRFs) for labeling sequential data.  
control: vcpkg/ports/crfsuite/CONTROL

Source: crossguid  
Version: 0.2.2-2018-06-16-1  
Build-Depends: libuuid (!windows&!uwp&!osx&!android)  
Description: CrossGuid is a minimal, cross platform, C++ GUID library.  
control: vcpkg/ports/crossguid/CONTROL

Source: crow  
Version: 0.1-1  
Homepage: https://github.com/ipkn/crow  
Description: Very fast and easy to use C++ micro web framework  
control: vcpkg/ports/crow/CONTROL

Source: cryptopp  
Version: 8.2.0  
Homepage: https://github.com/weidai11/cryptopp  
Description: Crypto++ is a free C++ class library of cryptographic schemes.  
control: vcpkg/ports/cryptopp/CONTROL

Source: ctbignum  
Version: 2019-08-02  
Homepage: https://github.com/niekbouman/ctbignum  
Description: This is a header-only template library for fixed-width "small big-integer" computations, for use during run-time as well as compile-time.  
Build-Depends: boost  
  
control: vcpkg/ports/ctbignum/CONTROL

Source: ctemplate  
Version:  2017-06-23-44b7c5-4  
Homepage: https://github.com/OlafvdSpek/ctemplate  
Description: C++ CTemplate system  
control: vcpkg/ports/ctemplate/CONTROL

Source: ctre  
Version: 2.6.4  
Description: A Compile time PCRE (almost) compatible regular expression matcher   
control: vcpkg/ports/ctre/CONTROL

Source: cub  
Version: 1.8.0  
Description: CUB is a flexible library of cooperative threadblock primitives and other utilities for CUDA kernel programming  
Build-Depends: cuda  
control: vcpkg/ports/cub/CONTROL

Source: cuda  
Version: 10.1  
Description: A parallel computing platform and programming model  
control: vcpkg/ports/cuda/CONTROL

Source: cudnn  
Version: 7.6  
Description: NVIDIA's cuDNN deep neural network acceleration library  
Build-Depends: cuda  
control: vcpkg/ports/cudnn/CONTROL

Source: cunit  
Version: 2.1.3-2  
Homepage: https://sourceforge.net/projects/cunit/  
Description: CUnit is a lightweight system for writing, administering, and running unit tests in C.  It provides C programmers a basic testing functionality with a flexible variety of user interfaces  
control: vcpkg/ports/cunit/CONTROL

Source: curl  
Version: 7.66.0  
Build-Depends: zlib  
Homepage: https://github.com/curl/curl  
Description: A library for transferring data with URLs  
Default-Features: ssl  
  
Feature: tool  
Description: Builds curl executable  
  
Feature: non-http  
Description: Enables protocols beyond HTTP/HTTPS/HTTP2  
  
Feature: http2  
Build-Depends: nghttp2, curl[ssl]  
Description: HTTP2 support  
  
Feature: ssl  
Build-Depends: curl[openssl] (!windows&!osx), curl[winssl] (windows), curl[sectransp] (osx)  
Description: Default SSL backend  
  
Feature: ssh  
Build-Depends: curl[openssl], libssh2, curl[non-http]  
Description: SSH support via libssh2  
  
# SSL backends  
Feature: openssl  
Build-Depends: openssl  
Description: SSL support (OpenSSL)  
  
Feature: winssl  
Description: SSL support (Secure Channel / "WinSSL")  
  
Feature: mbedtls  
Build-Depends: mbedtls  
Description: SSL support (mbedTLS)  
  
Feature: sectransp  
Description: SSL support (sectransp)  
  
Feature: c-ares  
Build-Depends: c-ares  
Description: c-ares support  
  
Feature:sspi  
Description: SSPI support   
  
Feature: brotli  
Description: brotli support (brotli)  
control: vcpkg/ports/curl/CONTROL

Source: curlpp  
Version: 2018-06-15  
Description: C++ wrapper around libcURL  
Build-Depends: curl  
control: vcpkg/ports/curlpp/CONTROL

Source: cute-headers  
Version: 2019-09-20  
Description: Collection of cross-platform one-file C/C++ libraries with no dependencies  
Homepage: https://github.com/RandyGaul/cute_headers  
control: vcpkg/ports/cute-headers/CONTROL

Source: cutelyst2  
Version: 2.8.0  
Description: A C++ Web Framework built on top of Qt, using the simple approach of Catalyst (Perl) framework  
Build-Depends: qt5-base  
control: vcpkg/ports/cutelyst2/CONTROL

Source: cxxopts  
Version: 2.2.0  
Homepage: https://github.com/jarro2783/cxxopts  
Description: This is a lightweight C++ option parser library, supporting the standard GNU style syntax for options  
control: vcpkg/ports/cxxopts/CONTROL

Source: czmq  
Version: 2019-06-10-3  
Build-Depends: zeromq  
Description: High-level C binding for ZeroMQ  
Homepage: https://github.com/zeromq/czmq  
  
Feature: tool  
Description: Build and install czmq tools (zmakecert)  
  
Feature: draft  
Description: Build and install draft APIs  
  
Feature: curl  
Description: Build with libcurl  
Build-Depends: curl  
  
Feature: lz4  
Description: Build with lz4  
Build-Depends: lz4  
  
Feature: httpd  
Description: Build with HTTP server support (libmicrohttpd)  
Build-Depends: libmicrohttpd  
  
Feature: uuid  
Description: Build with libuuid  
Build-Depends: libuuid (!windows&!uwp&!osx)  
control: vcpkg/ports/czmq/CONTROL

Source: darknet  
Version: 0.2.5.1  
Description: Darknet is an open source neural network framework written in C and CUDA. You only look once (YOLO) is a state-of-the-art, real-time object detection system, best example of darknet functionalities.  
Build-Depends: pthreads (windows), stb  
  
Feature: cuda  
Build-Depends: cuda  
Description: Build darknet with support for CUDA  
  
Feature: cudnn  
Build-Depends: darknet[cuda]  
Description: Build darknet with support for CUDNN  
  
Feature: opencv-base  
Build-Depends: opencv[ffmpeg]  
Description: Build darknet with support for OpenCV  
  
Feature: opencv-cuda  
Build-Depends: opencv[ffmpeg], opencv[cuda]  
Description: Build darknet with support for a CUDA-enabled OpenCV  
  
Feature: opencv3-base  
Build-Depends: opencv3[ffmpeg]  
Description: Build darknet with support for OpenCV3  
  
Feature: opencv3-cuda  
Build-Depends: opencv3[ffmpeg], opencv3[cuda]  
Description: Build darknet with support for a CUDA-enabled OpenCV3  
  
Feature: weights  
Description: Download pre-built weights for test  
  
Feature: weights-train  
Description: Download pre-built weights for training  
  
Feature: full  
Build-Depends: darknet[opencv-cuda], darknet[cudnn], darknet[weights], darknet[weights-train]  
Description: Build darknet fully-featured  
control: vcpkg/ports/darknet/CONTROL

Source: darts-clone  
Version:  1767ab87cffe-1  
Description: A static double-array trie structure  
control: vcpkg/ports/darts-clone/CONTROL

Source: date  
Version: 2019-09-09  
Homepage: https://github.com/HowardHinnant/date  
Description: A date and time library based on the C++17 <chrono> header  
  
Feature: remote-api  
Description: support automatic download of tz data  
Build-Depends: curl  
control: vcpkg/ports/date/CONTROL

Source: dbg-macro  
Version: 2019-07-11  
Description: A dbg(...) macro for C++  
Homepage: https://github.com/sharkdp/dbg-macro  
control: vcpkg/ports/dbg-macro/CONTROL

Source: dbow2  
Version: 2019-08-05  
Homepage: https://github.com/dorian3d/DBoW2  
Description: DBoW2 is an improved version of the DBow library, an open source C++ library for indexing and converting images into a bag-of-word representation.   
Build-Depends: opencv  
control: vcpkg/ports/dbow2/CONTROL

Source: dcmtk  
Version: 3.6.4-2  
Description: This DICOM ToolKit (DCMTK) package consists of source code, documentation and installation instructions for a set of software libraries and applications implementing part of the DICOM/MEDICOM Standard.  
control: vcpkg/ports/dcmtk/CONTROL

Source: decimal-for-cpp  
Version:1.16  
Description: Decimal data type support, for COBOL-like fixed-point operations on currency values.   
  
control: vcpkg/ports/decimal-for-cpp/CONTROL

Source: detours  
Version: 4.0.1  
Description: Detours is a software package for monitoring and instrumenting API calls on Windows.  
control: vcpkg/ports/detours/CONTROL

Source: devicenameresolver  
Version: 2016-06-26-0850d88fa6-1  
Description: a little library that resolves a path from a (virtual) device name.  
control: vcpkg/ports/devicenameresolver/CONTROL

Source: devil  
Version: 1.8.0-4  
Build-Depends:  
Homepage: https://github.com/DentonW/DevIL  
Description: A full featured cross-platform image library  
Default-Features: libpng, tiff, libjpeg, openexr, jasper, lcms  
  
Feature: libpng  
Build-Depends: libpng  
Description: Use Libpng for .png (and some .ico)  
  
Feature: tiff  
Build-Depends: tiff  
Description: Use Libtiff for .tif support  
  
Feature: libjpeg  
Build-Depends: libjpeg-turbo  
Description: Use Libjpeg for .jpg (and some .blp) support  
  
Feature: openexr  
Build-Depends: openexr  
Description: Use openexr  
  
Feature: jasper  
Build-Depends: jasper  
Description: Use JasPer for .jp2 (and some .icns) support  
  
Feature: lcms  
Build-Depends: lcms  
Description: Use Little CMS for color profiles  
control: vcpkg/ports/devil/CONTROL

Source: dimcli  
Version: 5.0.1  
Homepage: https://github.com/gknowles/dimcli  
Description: C++ command line parser toolkit  
control: vcpkg/ports/dimcli/CONTROL

Source: directxmesh  
Version: aug2019  
Homepage: https://walbourn.github.io/directxmesh  
Description: DirectXMesh geometry processing library  
control: vcpkg/ports/directxmesh/CONTROL

Source: directxtex  
Version: aug2019  
Homepage: https://walbourn.github.io/directxtex  
Description: DirectXTex texture processing library  
control: vcpkg/ports/directxtex/CONTROL

Source: directxtk  
Version: aug2019  
Homepage: https://walbourn.github.io/directxtk  
Description: A collection of helper classes for writing DirectX 11.x code in C++.  
control: vcpkg/ports/directxtk/CONTROL

Source: directxtk12  
Version: aug2019  
Homepage: https://walbourn.github.io/directx-tool-kit-for-directx-12  
Description: A collection of helper classes for writing DirectX 12 code in C++.  
control: vcpkg/ports/directxtk12/CONTROL

Source: dirent  
Version: 1.23.2  
Homepage: https://github.com/tronkko/dirent  
Description: Dirent is a C/C++ programming interface that allows programmers to retrieve information about files and directories under Linux/UNIX. This project provides Linux compatible Dirent interface for Microsoft Windows.  
control: vcpkg/ports/dirent/CONTROL

Source: discord-rpc  
Version: 3.4.0  
Homepage: https://github.com/discordapp/discord-rpc  
Description: Rich Presence allows you to leverage the totally overhauled "Now Playing" section in a Discord user's profile to help people play your game together.  
Build-Depends: rapidjson  
control: vcpkg/ports/discord-rpc/CONTROL

Source: discount  
Version: 2.2.6  
Homepage: https://github.com/Orc/discount  
Description: DISCOUNT is a implementation of John Gruber & Aaron Swartz's Markdown markup language.  
control: vcpkg/ports/discount/CONTROL

Source: distorm  
Version: 3.4.1  
Description: Powerful Disassembler Library For x86/AMD64  
control: vcpkg/ports/distorm/CONTROL

Source: dlfcn-win32  
Version: 1.1.1-3  
Homepage: https://github.com/dlfcn-win32/dlfcn-win32  
Description: dlfcn-win32 is an implementation of dlfcn for Windows.  
control: vcpkg/ports/dlfcn-win32/CONTROL

Source: dlib  
Version: 19.17-1  
Build-Depends: libjpeg-turbo, libpng, sqlite3, fftw3, openblas (!osx), clapack (!osx)  
Homepage: https://github.com/davisking/dlib  
Description: Modern C++ toolkit containing machine learning algorithms and tools for creating complex software in C++  
  
Feature: cuda  
Build-Depends: cuda  
Description: CUDA support for dlib  
control: vcpkg/ports/dlib/CONTROL

Source: dmlc  
Version: 2019-08-12  
Homepage: https://github.com/dmlc/dmlc-core  
Description: DMLC-Core is the backbone library to support all DMLC projects, offers the bricks to build efficient and scalable distributed machine learning libraries.  
Default-Features: openmp  
  
Feature: openmp  
Description: Build with openmp  
control: vcpkg/ports/dmlc/CONTROL

Source: docopt  
Version: 2018-11-01  
Description: Command line arguments parser that will make you smile (C++11 port).  
control: vcpkg/ports/docopt/CONTROL

Source: doctest  
Version: 2.3.5  
Homepage: https://github.com/onqtam/doctest  
Description: The fastest feature-rich C++ single-header testing framework for unit tests and TDD  
control: vcpkg/ports/doctest/CONTROL

Source: double-conversion  
Version: 3.1.5  
Homepage: https://github.com/google/double-conversion  
Description: Efficient binary-decimal and decimal-binary conversion routines for IEEE doubles.  
control: vcpkg/ports/double-conversion/CONTROL

Source: dpdk  
Version: 19.02  
Description: A set of libraries and drivers for fast packet processing  
  
control: vcpkg/ports/dpdk/CONTROL

Source: draco  
Version: 1.3.5  
Homepage: https://github.com/google/draco  
Description: A library for compressing and decompressing 3D geometric meshes and point clouds. It is intended to improve the storage and transmission of 3D graphics.  
Build-Depends:  
control: vcpkg/ports/draco/CONTROL

Source: drlibs  
Version: 2019-08-12  
Homepage: https://github.com/mackron/dr_libs  
Description: A collection of public domain single-file libraries for C/C++.  
control: vcpkg/ports/drlibs/CONTROL

Source: dtl  
Version: 1.19  
Description: Diff template library  
control: vcpkg/ports/dtl/CONTROL

Source: duckx  
Version: 2019-08-06  
Homepage: https://github.com/amiremohamadi/DuckX  
Description: DuckX is a library for creation of Office docx files.  
control: vcpkg/ports/duckx/CONTROL

Source: duilib  
Version: 2019-4-28-2  
Description: Duilib is a free open source DirectUI interface library under Windows. It is widely accepted by major Internet companies due to its simple and easy to expand design and stable and efficient implementation. It is widely used in IM, video client, stock market software, navigation software, and mobile phone assistive software. Duilib is still evolving, and will continue to improve in many aspects such as documentation, examples, animations, and rendering engines.  
control: vcpkg/ports/duilib/CONTROL

Source: duktape  
Version: 2.4.0-4  
Homepage: https://github.com/svaarala/duktape  
Description: Embeddable Javascript engine with a focus on portability and compact footprint.  
Build-Depends:  
control: vcpkg/ports/duktape/CONTROL

Source: dx  
Version: 1.0.1-1  
Homepage: https://github.com/sdcb/dx  
Description: A modern C++ library for DirectX programming  
control: vcpkg/ports/dx/CONTROL

Source: dxut  
Version: 11.14-3  
Homepage: https://github.com/Microsoft/DXUT  
Description: A "GLUT"-like framework for Direct3D 11.x Win32 desktop applications  
control: vcpkg/ports/dxut/CONTROL

Source: eastl  
Version: 3.14.01  
Homepage: https://github.com/electronicarts/EASTL  
Description: Electronic Arts Standard Template Library.  
  It is a C++ template library of containers, algorithms, and iterators useful for runtime and tool development across multiple platforms. It is a fairly extensive and robust implementation of such a library and has an emphasis on high performance above all other considerations.  
control: vcpkg/ports/eastl/CONTROL

Source: easycl  
Version: 0.3  
Homepage: https://github.com/architector1324/EasyCL  
Build-Depends: opencl  
Description: OpenCL based lightweight c++ computing library  
control: vcpkg/ports/easycl/CONTROL

Source: easyhook  
Version: 2.7.6789.0  
Homepage: https://github.com/EasyHook/EasyHook  
Description: This project supports extending (hooking) unmanaged code (APIs) with pure managed ones, from within a fully managed environment on 32- or 64-bit Windows Vista x64, Windows Server 2008 x64, Windows 7, Windows 8.1, and Windows 10.  
control: vcpkg/ports/easyhook/CONTROL

Source: easyloggingpp  
Version: 9.96.7-1  
Description: Easylogging++ is a single header efficient logging library for C++ applications.  
control: vcpkg/ports/easyloggingpp/CONTROL

Source: ebml  
Version: 1.3.9  
Homepage: https://github.com/Matroska-Org/libebml  
Description: a C++ libary to parse EBML files  
control: vcpkg/ports/ebml/CONTROL

Source: ecm  
Version: 5.60.0-1  
Homepage: https://github.com/KDE/extra-cmake-modules  
Description: Extra CMake Modules (ECM), extra modules and scripts for CMake  
control: vcpkg/ports/ecm/CONTROL

Source: ecsutil  
Version: 1.0.7.3  
Description: Native Windows SDK for accessing ECS via the S3 HTTP protocol.  
Build-Depends: atlmfc (windows)  
control: vcpkg/ports/ecsutil/CONTROL

Source: effolkronium-random  
Version: 1.3.0  
Description: Random with a modern C++ API  
control: vcpkg/ports/effolkronium-random/CONTROL

Source: egl-registry  
Version: 2019-08-08  
Description: the EGL API and Extension Registry  
control: vcpkg/ports/egl-registry/CONTROL

Source: eigen3  
Version: 3.3.7-3  
Homepage: https://bitbucket.org/eigen/eigen  
Description: C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.  
control: vcpkg/ports/eigen3/CONTROL

Source: embree2  
Version: 2.17.7  
Homepage: https://github.com/embree/embree  
Description: High Performance Ray Tracing Kernels.  
Build-Depends: tbb  
control: vcpkg/ports/embree2/CONTROL

Source: embree3  
Version: 3.5.2-2  
Homepage: https://github.com/embree/embree  
Description: High Performance Ray Tracing Kernels.  
Build-Depends: tbb  
control: vcpkg/ports/embree3/CONTROL

Source: enet  
Version: 1.3.13-1  
Homepage: https://github.com/lsalzman/enet  
Description: Reliable UDP networking library  
  
control: vcpkg/ports/enet/CONTROL

Source: ensmallen  
Version: 1.15.1  
Description: A header-only C++ library for mathematical optimization.  
Build-Depends: openblas (!osx), clapack (!osx), armadillo  
  
control: vcpkg/ports/ensmallen/CONTROL

Source: entityx  
Version: 1.3.0-1  
Description: EntityX - A fast, type-safe C++ Entity-Component system.  
Homepage: https://github.com/alecthomas/entityx  
control: vcpkg/ports/entityx/CONTROL

Source: entt  
Version: 3.1.1  
Description: Gaming meets modern C++ - a fast and reliable entity-component system and much more.  
Homepage: https://github.com/skypjack/entt  
control: vcpkg/ports/entt/CONTROL

Source: epsilon  
Version: 0.9.2  
Homepage: https://sourceforge.net/projects/epsilon-project/  
Description: EPSILON is an Open Source wavelet image compressor, that is aimed on parallel and robust image processing.  
control: vcpkg/ports/epsilon/CONTROL

Source: esaxx  
Version: ca7cb332011ec37  
Description: This library provides the implementation of enhanced suffix array.  
control: vcpkg/ports/esaxx/CONTROL

Source: evpp  
Version: 0.7.0-1  
Homepage: https://github.com/Qihoo360/evpp  
Description: A modern C++ network library based on libevent for developing high performance network services in TCP/UDP/HTTP protocols.  
Build-Depends: glog, libevent, rapidjson, concurrentqueue (!windows), boost-lockfree (!windows)  
control: vcpkg/ports/evpp/CONTROL

Source: exiv2  
Version: 0.27.2-1  
Build-Depends: zlib, expat, libiconv, gettext  
Description: Image metadata library and tools  
Homepage: https://www.exiv2.org  
  
Feature: unicode  
Description: Compile with unicode support on windows  
control: vcpkg/ports/exiv2/CONTROL

Source: expat  
Version: 2.2.7  
Homepage: https://github.com/libexpat/libexpat  
Description: XML parser library written in C  
control: vcpkg/ports/expat/CONTROL

Source: expected-lite  
Version: 0.3.0  
Description: Expected objects in C++11 and later in a single-file header-only library  
control: vcpkg/ports/expected-lite/CONTROL

Source: exprtk  
Version: 2019-07-11  
Homepage: https://github.com/ArashPartow/exprtk  
Description: Simple to use, easy to integrate and extremely efficient run-time C++ mathematical expression parser and evaluation engine.  
control: vcpkg/ports/exprtk/CONTROL

Source: fadbad  
Version: 2.1.0  
Homepage: https://www.fadbad.com/  
Description:  FADBAD++ Templates for Automatic Differentiation  
control: vcpkg/ports/fadbad/CONTROL

Source: fann  
Version: 2.2.0-1  
Description: Fast Artificial Neural Network (FANN) Library is a free open source neural network library, which implements multilayer artificial neural networks in C with support for both fully connected and sparsely connected networks.  
control: vcpkg/ports/fann/CONTROL

Source: fast-cpp-csv-parser  
Version: 2019-08-14  
Description: A small, easy-to-use and fast header-only library for reading comma separated value (CSV) files  
Homepage: https://github.com/ben-strasser/fast-cpp-csv-parser  
control: vcpkg/ports/fast-cpp-csv-parser/CONTROL

Source: fastcdr  
Version: 1.0.11  
Description: eProsima FastCDR is a C++ library that provides two serialization mechanisms. One is the standard CDR serialization mechanism, while the other is a faster implementation that modifies the standard.  
control: vcpkg/ports/fastcdr/CONTROL

Source: fastfeat  
Version: 391d5e9-1  
Description: FAST feature detectors in C  
control: vcpkg/ports/fastfeat/CONTROL

Source: fastlz  
Version: 1.0-3  
Homepage: https://github.com/ariya/FastLZ  
Description: A lightning-fast lossless compression library  
control: vcpkg/ports/fastlz/CONTROL

Source: fastrtps  
Version: 1.5.0-2  
Description: Eprosima Fast RTPS is a C++ implementation of the RTPS (Real Time Publish Subscribe) protocol, which provides publisher-subscriber communications over unreliable transports such as UDP, as defined and maintained by the Object Management Group (OMG) consortium.  
Build-Depends: openssl, asio, tinyxml2  
control: vcpkg/ports/fastrtps/CONTROL

Source: fcl  
Version: 0.5.0-6  
Homepage: https://github.com/flexible-collision-library/fcl  
Description: a library for performing three types of proximity queries on a pair of geometric models composed of triangles  
Build-Depends: ccd, octomap  
control: vcpkg/ports/fcl/CONTROL

Source: fdk-aac  
Version: 2018-07-08-1  
Homepage: https://github.com/mstorsjo/fdk-aac  
Description: A standalone library of the Fraunhofer FDK AAC code  
control: vcpkg/ports/fdk-aac/CONTROL

Source: fdlibm  
Version: 5.3-4  
Description: FDLIBM (Freely Distributable LIBM) is a C math library for machines that support IEEE 754 floating-point arithmetic  
control: vcpkg/ports/fdlibm/CONTROL

Source: ffmpeg  
Version: 4.2  
Build-Depends: zlib  
Homepage: https://ffmpeg.org  
Description: a library to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created.  
  FFmpeg is the leading multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge. No matter if they were designed by some standards committee, the community or a corporation. It is also highly portable: FFmpeg compiles, runs, and passes our testing infrastructure FATE across Linux, Mac OS X, Microsoft Windows, the BSDs, Solaris, etc. under a wide variety of build environments, machine architectures, and configurations.  
Default-Features: avresample  
  
Feature: ffmpeg  
Description: build the ffmpeg.exe application  
  
Feature: ffserver  
Description: ffserver appplication support in ffmpeg  
  
Feature: ffplay  
Description: ffplay appplication support in ffmpeg  
  
Feature: ffprobe  
Description: ffprobe appplication support in ffmpeg  
  
Feature: openssl  
Build-Depends: openssl, ffmpeg[nonfree]  
Description: openssl support in ffmpeg  
  
Feature: lzma  
Build-Depends: liblzma  
Description: lzma support in ffmpeg  
  
Feature: bzip2  
Build-Depends: bzip2  
Description: bzip2 support in ffmpeg  
  
Feature: vpx  
Build-Depends: libvpx  
Description: WebM VP8/VP9 support in ffmpeg  
  
Feature: x264  
Build-Depends: x264, ffmpeg[gpl]  
Description: x264 support in ffmpeg  
  
Feature: opencl  
Build-Depends: opencl  
Description: opencl support in ffmpeg  
  
Feature: nonfree  
Description: allow nonfree and unredistributable libraries  
  
Feature: gpl  
Description: allow GPL licensed libraries  
  
Feature: avresample  
Description: Libav audio resampling library support in ffmpeg  
control: vcpkg/ports/ffmpeg/CONTROL

Source: fftw3  
Version: 3.3.8-6  
Homepage: https://www.fftw.org/  
Description: FFTW is a C subroutine library for computing the discrete Fourier transform (DFT) in one or more dimensions, of arbitrary input size, and of both real and complex data (as well as of even/odd data, i.e. the discrete cosine/sine transforms or DCT/DST).  
  
Feature: openmp  
Description: Builds openmp enabled lib  
  
Feature: sse  
Description: Builds part of the library with sse  
  
Feature: sse2  
Description: Builds part of the library with sse2, sse  
  
Feature: avx  
Description: Builds part of the library with avx, sse2, sse  
  
Feature: avx2  
Description: Builds part of the library with avx2, fma, avx, sse2, sse  
  
Feature: threads  
Description: Enable threads in fftw3  
control: vcpkg/ports/fftw3/CONTROL

Source: field3d  
Version: 1.7.2  
Homepage: https://github.com/imageworks/Field3D  
Description: An open source library for storing voxel data. It provides C++ classes that handle in-memory storage and a file format based on HDF5 that allows the C++ objects to be written to and read from disk.  
Build-Depends: hdf5, boost-regex, boost-thread, boost-program-options, boost-system, openexr, boost-foreach, boost-test, boost-timer, boost-format  
control: vcpkg/ports/field3d/CONTROL

Source: fizz  
Version: 2019.07.08.00  
Build-Depends: folly, openssl, libsodium, zlib  
Description: a TLS 1.3 implementation by Facebook  
control: vcpkg/ports/fizz/CONTROL

Source: flann  
Version: 2019-04-07-1  
Homepage: https://github.com/mariusmuja/flann  
Build-Depends: lz4  
Description: Fast Library for Approximate Nearest Neighbors  
control: vcpkg/ports/flann/CONTROL

Source: flatbuffers  
Version: 1.11.0-1  
Description: Memory Efficient Serialization Library  
 FlatBuffers is an efficient cross platform serialization library for games and other memory constrained apps. It allows you to directly access serialized data without unpacking/parsing it first, while still having great forwards/backwards compatibility.  
Homepage:  https://google.github.io/flatbuffers/  
control: vcpkg/ports/flatbuffers/CONTROL

Source: flint  
Version: 2.5.2-3  
Homepage: https://www.flintlib.org/  
Description: Fast Library for Number Theory  
Build-Depends: mpir, mpfr, pthreads, gettimeofday  
control: vcpkg/ports/flint/CONTROL

Source: fltk  
Version: 1.3.4-7  
Homepage: https://www.fltk.org/  
Description: FLTK (pronounced fulltick) is a cross-platform C++ GUI toolkit for UNIX/Linux (X11), Microsoft Windows, and MacOS X. FLTK provides modern GUI functionality without the bloat and supports 3D graphics via OpenGL and its built-in GLUT emulation.  
Build-Depends: zlib, libpng, libjpeg-turbo  
control: vcpkg/ports/fltk/CONTROL

Source: fluidsynth  
Version: 2.0.5-1  
Description: FluidSynth reads and handles MIDI events from the MIDI input device. It is the software analogue of a MIDI synthesizer. FluidSynth can also play midifiles using a Soundfont.  
Build-Depends: glib  
control: vcpkg/ports/fluidsynth/CONTROL

Source: fmem  
Version: c-libs-2ccee3d2fb  
Description: A cross-platform library for opening memory-backed libc streams.  
control: vcpkg/ports/fmem/CONTROL

Source: fmi4cpp  
Version: 0.7.0-2  
Homepage: https://github.com/NTNU-IHB/FMI4cpp  
Description: FMI 2.0 implementation written in modern C++  
Build-Depends: boost-property-tree, libzip[openssl]  
  
Feature: curl  
Build-Depends: curl  
Description: Allows loading FMUs from URL  
  
Feature: odeint  
Build-Depends: boost-ublas, boost-odeint  
Description: Adds support for wrapping Model Exchange models as Co-simulation models using odeint solvers  
  
  
control: vcpkg/ports/fmi4cpp/CONTROL

Source: fmilib  
Version: 2.0.3-2  
Description: FMI library is intended as a foundation for applications interfacing FMUs (Functional Mockup Units) that follow FMI Standard. This version of the library supports FMI 1.0 and FMI2.0.  
Homepage: https://www.fmi-standard.org/  
control: vcpkg/ports/fmilib/CONTROL

Source: fmt  
Version: 6.0.0  
Homepage: https://github.com/fmtlib/fmt  
Description: Formatting library for C++. It can be used as a safe alternative to printf or as a fast alternative to IOStreams.  
control: vcpkg/ports/fmt/CONTROL

Source: folly  
Version: 2019.06.17.00  
Homepage: https://github.com/facebook/folly  
Description: An open-source C++ library developed and used at Facebook. The library is UNSTABLE on Windows  
Build-Depends: openssl, libevent, double-conversion, glog, gflags, boost-chrono, boost-context, boost-conversion, boost-crc, boost-date-time, boost-filesystem, boost-multi-index, boost-program-options, boost-regex, boost-system, boost-thread, boost-smart-ptr  
Default-Features: zlib  
  
Feature: zlib  
Build-Depends: zlib  
Description: Support zlib for compression  
  
Feature: bzip2  
Build-Depends: bzip2  
Description: Support bzip2 for compression  
  
Feature: lzma  
Build-Depends: liblzma  
Description: Support LZMA for compression  
  
Feature: zstd  
Build-Depends: zstd  
Description: Support zstd for compression  
  
Feature: snappy  
Build-Depends: snappy  
Description: Support Snappy for compression  
  
Feature: lz4  
Build-Depends: lz4  
Description: Support lz4 for compression  
control: vcpkg/ports/folly/CONTROL

Source: fontconfig  
Version: 2.12.4-9  
Homepage: https://www.freedesktop.org/software/fontconfig/front.html  
Description: Library for configuring and customizing font access.  
Build-Depends: freetype, expat, libiconv, dirent  
control: vcpkg/ports/fontconfig/CONTROL

Source: foonathan-memory  
Version: 2019-07-21-1  
Description: STL compatible C++ memory allocator library  
Homepage: https://foonathan.net/doc/memory/  
Default-Features: tool  
  
Feature: tool  
Description: Build foonathan memory tool  
control: vcpkg/ports/foonathan-memory/CONTROL

Source: forest  
Version: 12.0.3  
Homepage: https://github.com/xorz57/forest  
Description: Template Library of Tree Data Structures in C++17  
control: vcpkg/ports/forest/CONTROL

Source: forge  
Version: 1.0.4-1  
Description: Helps with high performance visualizations involving OpenGL-CUDA/OpenCL interop.  
Build-Depends: glfw3, glm, glbinding, freetype, boost-functional, freeimage, fontconfig (!windows)  
control: vcpkg/ports/forge/CONTROL

Source: fplus  
Version: 0.2.3-p0  
Description: Functional Programming Library for C++. Write concise and readable C++ code.   
Homepage: https://github.com/Dobiasd/FunctionalPlus  
control: vcpkg/ports/fplus/CONTROL

Source: freeglut  
Version: 3.0.0-7  
Homepage: https://sourceforge.net/projects/freeglut/  
Description: Open source implementation of GLUT with source and binary backwards compatibility.  
control: vcpkg/ports/freeglut/CONTROL

Source: freeimage  
Version: 3.18.0-7  
Build-Depends: zlib, libpng, libjpeg-turbo, tiff, openjpeg, libwebp[all] (!uwp), libraw, jxrlib, openexr  
Homepage: https://sourceforge.net/projects/freeimage/  
Description: Support library for graphics image formats  
control: vcpkg/ports/freeimage/CONTROL

Source: freeopcua  
Version: 20190125-2  
Description: OPC-UA server and client library written in C++ and with a lot of code auto-generated from xml specification using python.  
Build-Depends: boost-asio,boost-system,boost-program-options,boost-filesystem,boost-thread,boost-format,boost-foreach,boost-property-tree,boost-date-time  
control: vcpkg/ports/freeopcua/CONTROL

Source: freerdp  
Version: 2.0.0-rc4-2  
Homepage: https://github.com/FreeRDP/FreeRDP  
Description: A free implementation of the Remote Desktop Protocol (RDP)  
Build-Depends: openssl  
control: vcpkg/ports/freerdp/CONTROL

Source: freetds  
Version: 1.1.6-1  
Homepage: https://www.freetds.org  
Description: Implementation of the Tabular Data Stream protocol  
Default-Features: openssl  
  
Feature: openssl  
Build-Depends: openssl  
Description: OpenSSL support  
control: vcpkg/ports/freetds/CONTROL

Source: freetype  
Version: 2.10.1-1  
Build-Depends: zlib, bzip2, libpng  
Homepage: https://www.freetype.org/  
Description: A library to render fonts.  
control: vcpkg/ports/freetype/CONTROL

Source: freetype-gl  
Version: 2019-03-29-1  
Homepage: https://github.com/rougier/freetype-gl  
Description: OpenGL text using one vertex buffer, one texture and FreeType  
Build-Depends: glew, freetype  
control: vcpkg/ports/freetype-gl/CONTROL

Source: freexl  
Version: 1.0.4-2  
Homepage: https://www.gaia-gis.it/gaia-sins/freexl-sources  
Description: FreeXL is an open source library to extract valid data from within an Excel (.xls) spreadsheet  
Build-Depends: libiconv  
  
control: vcpkg/ports/freexl/CONTROL

Source: fribidi  
Version: 2019-02-04-1  
Description: GNU FriBidi is an implementation of the Unicode Bidirectional Algorithm (bidi)  
control: vcpkg/ports/fribidi/CONTROL

Source: fruit  
Version: 3.4.0-1  
Description: Fruit, a dependency injection framework for C++ by Google  
  
control: vcpkg/ports/fruit/CONTROL

Source: ftgl  
Version: 2.4.0-1  
Description: FTGL is a free open source library to enable developers to use arbitrary fonts in their OpenGL (www.opengl.org) applications.  
  Unlike other OpenGL font libraries FTGL uses standard font file formats so doesn't need a preprocessing step to convert the high quality font data into a lesser quality, proprietary format.  
  FTGL uses the Freetype (www.freetype.org) font library to open and 'decode' the fonts. It then takes that output and stores it in a format most efficient for OpenGL rendering.  
Build-Depends: freetype, opengl  
control: vcpkg/ports/ftgl/CONTROL

Source: fuzzylite  
Version: 6.0-2  
Homepage: https://github.com/fuzzylite/fuzzylite  
Description: A fuzzy logic control library in C++  
control: vcpkg/ports/fuzzylite/CONTROL

Source: g2o  
Version: 20170730_git-5  
Build-Depends: suitesparse, eigen3, clapack (!osx), ceres  
Description: g2o: A General Framework for Graph Optimization  
Homepage: https://openslam.org/g2o.html  
control: vcpkg/ports/g2o/CONTROL

Source: g3log  
Version: 2019-07-29  
Description: Asynchronous logger with Dynamic Sinks  
Homepage: https://github.com/KjellKod/g3log  
control: vcpkg/ports/g3log/CONTROL

Source: gainput  
Version: 1.0.0-2  
Homepage: https://github.com/jkuhlmann/gainput  
Description: Gainput is a multiplatform C++ input library, supporting mouse, keyboard and controllers  
control: vcpkg/ports/gainput/CONTROL

Source: gamma  
Version: gamma-2018-01-27-1  
Build-Depends: libsndfile, portaudio  
Description: Gamma is a cross-platform, C++ library for doing generic synthesis and filtering of signals. It is oriented towards real-time sound and graphics applications, but is equally useful for non-real-time tasks. Gamma is designed to be "light-footed" in terms of memory and processing making it highly suitable for plug-in development or embedding in other C++ projects.  
control: vcpkg/ports/gamma/CONTROL

Source: gaussianlib  
Version: 2019-08-04  
Description: Basic linear algebra C++ library for 2D and 3D applications  
Homepage: https://github.com/LukasBanana/GaussianLib  
control: vcpkg/ports/gaussianlib/CONTROL

Source: gcem  
Version: 1.12.0  
Description: A C++ compile-time math library using generalized constant expressions  
control: vcpkg/ports/gcem/CONTROL

Source: gdal  
Version: 2.4.1-8  
Homepage: https://gdal.org/  
Description: The Geographic Data Abstraction Library for reading and writing geospatial raster and vector data.  
Build-Depends: proj, libpng, geos, sqlite3, curl, expat, libpq, openjpeg, libwebp, libxml2, liblzma, netcdf-c, hdf5, zlib  
  
Feature: mysql-libmariadb  
Build-Depends: libmariadb  
Description: Add mysql support using libmariadb  
  
Feature: libspatialite  
Build-Depends: libspatialite  
Description: Create or update SpatiaLite databases using libspatialite  
control: vcpkg/ports/gdal/CONTROL

Source: gdcm  
Version: 3.0.0-5  
Description: Grassroots DICOM library  
Build-Depends: zlib, expat, openjpeg  
control: vcpkg/ports/gdcm/CONTROL

Source: gdcm2  
Version: deprecated  
Homepage: https://github.com/malaterre/GDCM  
Description: This port was renamed to gdcm.  The gdcm2 name is deprecated.  
Build-Depends: gdcm  
control: vcpkg/ports/gdcm2/CONTROL

Source: gdk-pixbuf  
Version: 2.36.9-3  
Homepage: https://developer.gnome.org/gdk-pixbuf/  
Description: Image loading library.  
Build-Depends: gettext, zlib, libpng, glib  
control: vcpkg/ports/gdk-pixbuf/CONTROL

Source: genann  
Version: 2019-07-10  
Homepage: https://github.com/codeplea/genann  
Description: Genann is a minimal, well-tested library for training and using feedforward artificial neural networks (ANN) in C.  
control: vcpkg/ports/genann/CONTROL

Source: geogram  
Version: 1.6.9-7  
Homepage: https://gforge.inria.fr/projects/geogram/  
Description: Geogram is a programming library of geometric algorithms.  
Build-Depends: openblas (!osx), clapack (!osx)  
  
Feature: graphics  
Description: Build viewers and geogram_gfx library.  
Build-Depends: glfw3  
control: vcpkg/ports/geogram/CONTROL

Source: geographiclib  
Version: 1.47-patch1-9  
Homepage: https://sourceforge.net/projects/geographiclib/  
Description: a small set of C++ classes for performing conversions between geographic, UTM, UPS, MGRS, geocentric, and local cartesian coordinates, for gravity (e.g., EGM2008), geoid height, and geomagnetic field (e.g., WMM2010) calculations, and for solving geodesic problems.  
control: vcpkg/ports/geographiclib/CONTROL

Source: geos  
Version: 3.6.3-3  
Homepage: https://www.osgeo.org/projects/geos/  
Description: Geometry Engine Open Source  
control: vcpkg/ports/geos/CONTROL

Source: geotrans  
Version: 3.7  
Description: Geotrans is a library that allows you convert geographic coordinates among a wide variety of coordinate systems, map projections, and datums.  
control: vcpkg/ports/geotrans/CONTROL

Source: getopt  
Version: 0  
Description: The getopt and getopt_long functions automate some of the chore involved in parsing typical unix command line options.  
Build-Depends: getopt-win32 (windows)  
control: vcpkg/ports/getopt/CONTROL

Source: getopt-win32  
Version: 0.1  
Description: An implementation of getopt.  
Homepage: https://github.com/libimobiledevice-win32  
control: vcpkg/ports/getopt-win32/CONTROL

Source: gettext  
Version: 0.19-11  
Homepage: https://www.gnu.org/software/gettext/  
Description: The GNU gettext utilities are a set of tools that provides a framework to help other GNU packages produce multi-lingual messages. Provides libintl.  
Build-Depends: libiconv  
control: vcpkg/ports/gettext/CONTROL

Source: gettimeofday  
Version: 2017-10-14-2  
Description: An implementation of gettimeofday for WIN32  
control: vcpkg/ports/gettimeofday/CONTROL

Source: gflags  
Version: 2.2.2-1  
Homepage: https://github.com/gflags/gflags  
Description: A C++ library that implements commandline flags processing  
control: vcpkg/ports/gflags/CONTROL

Source: gherkin-c  
Version: 2019-10-07-1  
Description: Gherkin parser/compiler in C   
control: vcpkg/ports/gherkin-c/CONTROL

Source: giflib  
Version: 5.1.4-3  
Homepage: https://sourceforge.net/projects/giflib/  
Description: A library for reading and writing gif images.  
control: vcpkg/ports/giflib/CONTROL

Source: gl2ps  
Version: 1.4.0-3  
Homepage: https://gitlab.onelab.info/gl2ps/gl2ps  
Description: OpenGL to PostScript Printing Library  
Build-Depends: freeglut, zlib, libpng  
control: vcpkg/ports/gl2ps/CONTROL

Source: gl3w  
Version: 2018-05-31-1  
Homepage: https://github.com/skaslev/gl3w  
Description: Simple OpenGL core profile loading  
Build-Depends: opengl-registry  
control: vcpkg/ports/gl3w/CONTROL

Source: glad  
Version: 0.1.31  
Description: Multi-Language Vulkan/GL/GLES/EGL/GLX/WGL Loader-Generator based on the official specs.  
Build-Depends: egl-registry, opengl-registry  
control: vcpkg/ports/glad/CONTROL

Source: glbinding  
Version: 3.1.0-2  
Description: glbinding is an MIT licensed, cross-platform C++ binding for the OpenGL API  
Homepage: https://github.com/cginternals/glbinding  
Build-Depends: egl-registry  
control: vcpkg/ports/glbinding/CONTROL

Source: glew  
Version: 2.1.0-6  
Description: The OpenGL Extension Wrangler Library (GLEW) is a cross-platform open-source C/C++ extension loading library.  
Homepage: https://github.com/nigels-com/glew  
control: vcpkg/ports/glew/CONTROL

Source: glfw3  
Version: 3.3-2  
Homepage: https://github.com/glfw/glfw  
Description: GLFW is a free, Open Source, multi-platform library for OpenGL, OpenGL ES and Vulkan application development. It provides a simple, platform-independent API for creating windows, contexts and surfaces, reading input, handling events, etc.  
control: vcpkg/ports/glfw3/CONTROL

Source: gli  
Version: dd17acf  
Build-Depends: glm  
Description: OpenGL Image (GLI)  
Homepage: https://gli.g-truc.net  
control: vcpkg/ports/gli/CONTROL

Source: glib  
Version: 2.52.3-14-3  
Homepage: https://developer.gnome.org/glib/  
Description: Portable, general-purpose utility library.  
Build-Depends: zlib, pcre, libffi, gettext, libiconv  
  
Feature: selinux  
Description: Build with selinux support.  
control: vcpkg/ports/glib/CONTROL

Source: glibmm  
Version: 2.52.1-9  
Description: This is glibmm, a C++ API for parts of glib that are useful for C++.  
Homepage: https://www.gtkmm.org.  
Build-Depends: zlib, pcre, libffi, gettext, libiconv, glib, libsigcpp  
control: vcpkg/ports/glibmm/CONTROL

Source: glm  
Version: 0.9.9.5-3  
Description: OpenGL Mathematics (GLM)  
Homepage: https://glm.g-truc.net  
control: vcpkg/ports/glm/CONTROL

Source: globjects  
Version: 1.1.0-2  
Build-Depends: glbinding, glm  
Description: C++ library strictly wrapping OpenGL objects.  
Homepage: https://github.com/cginternals/globjects  
control: vcpkg/ports/globjects/CONTROL

Source: glog  
Version: 0.4.0-2  
Homepage: https://github.com/google/glog  
Description: C++ implementation of the Google logging module  
Build-Depends: gflags  
control: vcpkg/ports/glog/CONTROL

Source: glslang  
Version: 2019-03-05-1  
Homepage: https://github.com/KhronosGroup/glslang  
Description: Khronos reference front-end for GLSL and ESSL, and sample SPIR-V generator  
control: vcpkg/ports/glslang/CONTROL

Source: gmime  
Version: 3.2.3-1  
Build-Depends: zlib, glib, libiconv, libidn2  
Homepage: https://developer.gnome.org/gmime/  
Description: GMime is a C/C++ library which may be used for the creation and parsing of messages using the Multipurpose Internet Mail Extension (MIME).  
control: vcpkg/ports/gmime/CONTROL

Source: gmmlib  
Version: 19.2.3  
Description: intel's graphics memory management library  
control: vcpkg/ports/gmmlib/CONTROL

Source: google-cloud-cpp  
Version: 0.14.0  
Build-Depends: grpc, curl[ssl], crc32c, googleapis  
Description: C++ Client Libraries for Google Cloud Platform APIs.  
Homepage: https://github.com/googleapis/google-cloud-cpp  
control: vcpkg/ports/google-cloud-cpp/CONTROL

Source: googleapis  
Version: 0.1.5  
Build-Depends: grpc, protobuf  
Description: C++ Proto Libraries for Google APIs.  
Homepage: https://github.com/googleapis/cpp-cmakefiles  
control: vcpkg/ports/googleapis/CONTROL

Source: gppanel  
Version: 2018-04-06  
Build-Depends: wxwidgets  
Homepage: https://github.com/woollybah/gppanel  
Description: gpPanel is chart libary for wxWidget. It inheritance from wxPanel and use modified wxMathPlot library at chart engine.   
control: vcpkg/ports/gppanel/CONTROL

Source: graphicsmagick  
Maintainer: josuegomes@gmail.com  
Version: 1.3.33  
Build-Depends: zlib, bzip2, freetype, libjpeg-turbo, libpng, tiff  
Homepage: https://sourceforge.net/projects/graphicsmagick/  
Description: Image processing library  
control: vcpkg/ports/graphicsmagick/CONTROL

Source: graphite2  
Version: 1.3.13  
Homepage: https://github.com/silnrsi/graphite  
Description: Graphite is a "smart font" system developed specifically to handle the complexities of lesser-known languages of the world.  
  Graphite2 is a rework of the original Graphite engine that is faster, smaller, and uses an API that is better suited to the layout architecture of most text-processing applications.  
control: vcpkg/ports/graphite2/CONTROL

Source: graphqlparser  
Version: 0.7.0-1  
Description: A GraphQL query parser in C++ with C and C++ APIs  
control: vcpkg/ports/graphqlparser/CONTROL

Source: greatest  
Version: 1.4.2  
Description: Single-file testing system for C  
Homepage: https://github.com/silentbicycle/greatest  
control: vcpkg/ports/greatest/CONTROL

Source: grpc  
Version: 1.23.1  
Build-Depends: zlib, openssl, protobuf, c-ares (!uwp)  
Homepage: https://github.com/grpc/grpc  
Description: An RPC library and framework  
control: vcpkg/ports/grpc/CONTROL

Source: grppi  
Version: 0.4.0  
Homepage: https://github.com/arcosuc3m/grppi  
Description: GrPPI is an open source generic and reusable parallel pattern programming interface developed at University Carlos III of Madrid.    
control: vcpkg/ports/grppi/CONTROL

Source: gsl  
Version: 2.4-3  
Homepage: https://www.gnu.org/software/gsl/  
Description: The GNU Scientific Library is a numerical library for C and C++ programmers  
control: vcpkg/ports/gsl/CONTROL

Source: gsl-lite  
Version: 0.28.0  
Homepage: https://github.com/martinmoene/gsl-lite  
Description: A single-file header-only version of ISO C++ Guideline Support Library (GSL) for C++98, C++11 and later  
control: vcpkg/ports/gsl-lite/CONTROL

Source: gsoap  
Version: 2.8.93-1  
Build-Depends: curl  
Homepage: https://sourceforge.net/projects/gsoap2/  
Description: The gSOAP toolkit is a C and C++ software development toolkit for SOAP and REST XML Web services and generic C/C++ XML data bindings.  
control: vcpkg/ports/gsoap/CONTROL

Source: gtest  
Version: 2019-08-14-2  
Homepage: https://github.com/google/googletest  
Description: GoogleTest and GoogleMock testing frameworks.  
control: vcpkg/ports/gtest/CONTROL

Source: gtk  
Version: 3.22.19-3  
Homepage: https://www.gtk.org/  
Description: Portable library for creating graphical user interfaces.  
Build-Depends: glib, atk, gdk-pixbuf, pango, cairo, libepoxy, gettext  
control: vcpkg/ports/gtk/CONTROL

Source: gtkmm  
Version: 3.22.2-1  
Homepage: https://www.gtkmm.org/  
Description: gtkmm is the official C++ interface for the popular GUI library GTK+.  
Build-Depends: glib, atk, gtk, gdk-pixbuf, pango, cairo, libepoxy, gettext, glibmm, atkmm, cairomm, pangomm  
control: vcpkg/ports/gtkmm/CONTROL

Source: gts  
Version: 0.7.6-1  
Homepage: https://github.com/finetjul/gts  
Description: A Library intended to provide a set of useful functions to deal with 3D surfaces meshed with interconnected triangles  
Build-Depends: glib  
control: vcpkg/ports/gts/CONTROL

Source: guetzli  
Version: 2018-07-30-2  
Homepage: https://github.com/google/guetzli  
Description: Perceptual JPEG encoder  
Build-Depends: libpng, butteraugli  
control: vcpkg/ports/guetzli/CONTROL

Source: gumbo  
Version: 0.10.1-3  
Homepage: https://github.com/google/gumbo-parser  
Description: An HTML5 parsing library in pure C99  
control: vcpkg/ports/gumbo/CONTROL

Source: halide  
Version: release_2019_08_27  
Homepage: https://github.com/halide/Halide  
Description: Halide is a programming language designed to make it easier to write high-performance image processing code on modern machines.  
Build-Depends: llvm, openblas  
  
Feature: app  
Description: app support  
  
Feature: tutorials  
Description: tutorials support  
  
Feature: utils  
Description: utils  
  
Feature: nativeclient  
Description: nativeclient  
  
Feature: hexagon  
Description: hexagon  
  
Feature: metal  
Description: metal support  
  
Feature: mips  
Description: mips support  
  
Feature: powerpc  
Description: powerpc support  
  
Feature: ptx  
Description: ptx support  
  
Feature: opencl  
Build-Depends: opencl  
Description: opencl support  
  
Feature: opengl  
Build-Depends: opengl  
Description: opengl support  
  
Feature: rtti  
Description: rtti support  
  
Feature: docs  
Description: docs  
  
Feature: test  
Description: test  
control: vcpkg/ports/halide/CONTROL

Source: harfbuzz  
Version: 2.5.3  
Description: HarfBuzz OpenType text shaping engine  
Homepage: https://github.com/behdad/harfbuzz  
Build-Depends: freetype, ragel, gettext (osx)  
Default-Features: ucdn  
  
Feature: graphite2  
Build-Depends: graphite2  
Description: Graphite2 shaper support  
  
Feature: icu  
Build-Depends: icu  
Description: icu support for harfbuzz  
  
Feature: ucdn  
Description: Builtin (UCDN) Unicode callbacks support  
  
Feature: glib  
Build-Depends: glib  
Description: Glib Unicode callbacks support  
control: vcpkg/ports/harfbuzz/CONTROL

Source: hayai  
Version: 2019-08-10  
Description: C++ benchmarking framework  
Homepage: https://github.com/nickbruun/hayai  
control: vcpkg/ports/hayai/CONTROL

Source: hdf5  
Version: 1.10.5-8  
Homepage: https://www.hdfgroup.org/downloads/hdf5/  
Description: HDF5 is a data model, library, and file format for storing and managing data  
Build-Depends: zlib, szip  
  
Feature: parallel  
Description: parallel support for HDF5  
Build-Depends: mpi  
  
Feature: cpp  
Description: Builds cpp lib  
control: vcpkg/ports/hdf5/CONTROL

Source: hedley  
Version: 2019-05-08-1  
Description: A C/C++ header to help move #ifdefs out of your code  
control: vcpkg/ports/hedley/CONTROL

Source: hfsm2  
Version: beta7  
Homepage: https://github.com/andrew-gresyk/HFSM2  
Description: Header-only heriarchical FSM framework in C++14, with fully statically-defined structure (no dynamic allocations), built with variadic templates.  
Build-Depends: catch2  
control: vcpkg/ports/hfsm2/CONTROL

Source: hidapi  
Version: 2019-08-30  
Description: A Simple library for communicating with USB and Bluetooth HID devices on Linux, Mac and Windows.  
Homepage: https://github.com/libusb/hidapi  
control: vcpkg/ports/hidapi/CONTROL

Source: highfive  
Version: 2.0  
Homepage: https://github.com/BlueBrain/HighFive  
Description: HighFive is a modern C++/C++11 friendly interface for libhdf5  
Build-Depends: hdf5  
control: vcpkg/ports/highfive/CONTROL

Source: hpx  
Version: 1.3.0-2  
Build-Depends: hwloc, boost-accumulators, boost-algorithm, boost-asio, boost-assign, boost-bimap, boost-chrono, boost-config, boost-context, boost-dynamic-bitset, boost-exception, boost-filesystem, boost-iostreams, boost-lockfree, boost-program-options, boost-range, boost-spirit, boost-system, boost-throw-exception, boost-variant, boost-winapi  
Homepage: https://github.com/STEllAR-GROUP/hpx  
Description: The C++ Standards Library for Concurrency and Parallelism  
  HPX is a C++ Standards Library for Concurrency and Parallelism. It implements all of the corresponding facilities as defined by the C++ Standard. Additionally, in HPX we implement functionalities proposed as part of the ongoing C++ standardization process. We also extend the C++ Standard APIs to the distributed case.  
control: vcpkg/ports/hpx/CONTROL

Source: http-parser  
Version: 2.9.2-1  
Homepage: https://github.com/nodejs/http-parser  
Description: HTTP Parser.  
control: vcpkg/ports/http-parser/CONTROL

Source: hungarian  
Version: v0.1.3  
Description: C-implementation of the Hungarian Method: finding the optimal assignment (assigning a set of jobs to a set of machines) in O(n^3), where n=max{#jobs, #machines}. The implementation is a sligntly enhanced version of the implementation provided by the Stanford GraphBase  
control: vcpkg/ports/hungarian/CONTROL

Source: hunspell  
Version: 1.7.0  
Homepage: https://github.com/hunspell/hunspell  
Description: The most popular spellchecking library.  
control: vcpkg/ports/hunspell/CONTROL

Source: hwloc  
Version: 1.11.7-3  
Homepage: https://github.com/open-mpi/hwloc  
Description: Portable Hardware Locality (hwloc)   
  The Portable Hardware Locality (hwloc) software package provides a portable abstraction (across OS, versions, architectures, ...) of the hierarchical topology of modern architectures, including NUMA memory nodes, sockets, shared caches, cores and simultaneous multithreading. It also gathers various system attributes such as cache and memory information as well as the locality of I/O devices such as network interfaces, InfiniBand HCAs or GPUs.   
control: vcpkg/ports/hwloc/CONTROL

Source: hyperscan  
Version: 5.0.1-1  
Description: A regular expression library with O(length of input) match times that takes advantage of Intel hardware to provide blazing speed.  
Build-Depends: boost-array, boost-chrono, boost-config, boost-core, boost-detail, boost-functional, boost-regex, boost-system, boost-thread, boost-type-traits, boost-unordered, boost-utility, boost-dynamic-bitset, boost-random, boost-graph, boost-multi-array, boost-icl, boost-ptr-container, python3, ragel  
control: vcpkg/ports/hyperscan/CONTROL

Source: hypre  
Version: 2.11.2-2  
Homepage: https://computation.llnl.gov/projects/hypre-scalable-linear-solvers-multigrid-methods  
Description: SCALABLE LINEAR SOLVERS AND MULTIGRID METHODS  
Build-Depends: mpi  
control: vcpkg/ports/hypre/CONTROL

Source: icu  
Version: 61.1-7  
Homepage: http://icu-project.org/apiref/icu4c/  
Description: Mature and widely used Unicode and localization library.  
control: vcpkg/ports/icu/CONTROL

Source: ideviceinstaller  
Version: 1.1.2.23-1  
Description: Manage apps of iOS devices  
Build-Depends: libimobiledevice, libzip  
control: vcpkg/ports/ideviceinstaller/CONTROL

Source: idevicerestore  
Version: 1.0.12-3  
Description: Restore/upgrade firmware of iOS devices  
Build-Depends: libimobiledevice, curl, libirecovery, libzip  
control: vcpkg/ports/idevicerestore/CONTROL

Source: if97  
Version: 2.1.2  
Homepage: https://github.com/CoolProp/IF97  
Description: This repository implements the IF97 formulation for the properties of pure water substance.  
control: vcpkg/ports/if97/CONTROL

Source: igloo  
Version: 1.1.1  
Description: A framework for unit testing in C++  
control: vcpkg/ports/igloo/CONTROL

Source: ignition-cmake0  
Version: 0.6.2-1  
Homepage: https://ignitionrobotics.org/libs/cmake  
Description: CMake helper functions for building robotic applications  
Build-Depends: ignition-modularscripts  
  
  
control: vcpkg/ports/ignition-cmake0/CONTROL

Source: ignition-common1  
Version: 1.1.1  
Build-Depends: dlfcn-win32 (windows|uwp), ffmpeg (!windows&!uwp), freeimage (!windows&!uwp), gts (!windows&!uwp), ignition-cmake0, ignition-math4, tinyxml2 (!windows&!uwp)  
Description: Common libraries for robotics applications  
control: vcpkg/ports/ignition-common1/CONTROL

Source: ignition-fuel-tools1  
Version: 1.2.0  
Build-Depends: curl, ignition-cmake0, ignition-common1, libyaml, libzip, jsoncpp  
Description: Tools for using fuel API to download robot models  
control: vcpkg/ports/ignition-fuel-tools1/CONTROL

Source: ignition-math4  
Version: 4.0.0  
Homepage: https://ignitionrobotics.org/libs/math  
Build-Depends: ignition-cmake0  
Description: Math API for robotic applications  
control: vcpkg/ports/ignition-math4/CONTROL

Source: ignition-modularscripts  
Version: 2019-09-11  
Description: Vcpkg helpers to package ignition libraries  
control: vcpkg/ports/ignition-modularscripts/CONTROL

Source: ignition-msgs1  
Version: 1.0.0  
Build-Depends: ignition-cmake0, ignition-math4, protobuf  
Description: Middleware protobuf messages for robotics  
control: vcpkg/ports/ignition-msgs1/CONTROL

Source: ignition-transport4  
Version: 4.0.0  
Build-Depends: cppzmq, ignition-cmake0, ignition-msgs1, libuuid (!windows&!uwp), protobuf, zeromq  
Description: Transport middleware for robotics  
control: vcpkg/ports/ignition-transport4/CONTROL

Source: ilmbase  
Version: 2.3.0  
Build-Depends: openexr  
Description: empty package, linking to newer one  
control: vcpkg/ports/ilmbase/CONTROL

Source: imgui  
Version: 1.72b  
Homepage: https://github.com/ocornut/imgui  
Description: Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies.  
control: vcpkg/ports/imgui/CONTROL

Source: imgui-sfml  
Version: 2.1  
Homepage: https://github.com/eliasdaler/imgui-sfml  
Description: ImGui binding for use with SFML  
Build-Depends: sfml, imgui  
control: vcpkg/ports/imgui-sfml/CONTROL

Source: immer  
Version: 2019-06-07  
Description: Postmodern immutable and persistent data structures for C++  
control: vcpkg/ports/immer/CONTROL

Source: inih  
Version: 45  
Description: Simple .INI file parser  
control: vcpkg/ports/inih/CONTROL

Source: inja  
Version: 2.1.0-1  
Build-Depends: nlohmann-json  
Description: Inja - A Template Engine for Modern C++  
control: vcpkg/ports/inja/CONTROL

Source: intel-ipsec  
Version: 0.52  
Description: Intel(R) Multi-Buffer Crypto for IPsec Library  
  
control: vcpkg/ports/intel-ipsec/CONTROL

Source: intel-mkl  
Version: 2018.0.1  
Description: Intel® Math Kernel Library (Intel® MKL) accelerates math processing routines, increases application performance, and reduces development time on Intel® processors.   
control: vcpkg/ports/intel-mkl/CONTROL

Source: intelrdfpmathlib  
Version: 20U2  
Description: Intel(R) Decimal Floating-Point Math Library  
control: vcpkg/ports/intelrdfpmathlib/CONTROL

Source: io2d  
Version: 2019-07-11-1  
Description: a lightweight, cross platform drawing library  
Build-Depends: cairo (!osx), cairo[x11] (linux), graphicsmagick (!osx)  
control: vcpkg/ports/io2d/CONTROL

Source: irrlicht  
Version: 1.8.4-2  
Homepage: http://irrlicht.sourceforge.net  
Description: Irrlicht lightning fast 3d engine  
Build-Depends: zlib, libpng, bzip2, libjpeg-turbo  
  
Feature: fast-fpu  
Description: Enable fast maths (at the expense of precision)  
  
Feature: tools  
Description: Build the Tools FileToHeader, FontTool, GUIEditor and MeshConverter  
control: vcpkg/ports/irrlicht/CONTROL

Source: isal  
Version: 2.25.0  
Description: Intel(R) Intelligent Storage Acceleration Library  
  
control: vcpkg/ports/isal/CONTROL

Source: ismrmrd  
Version: 1.4.0-1  
Description: ISMRM Raw Data Format  
Build-Depends: pugixml, hdf5, boost, fftw3  
control: vcpkg/ports/ismrmrd/CONTROL

Source: itk  
Version: 5.0.1-1  
Description: Insight Segmentation and Registration Toolkit (ITK) is used for image processing and analysis.  
Homepage: https://github.com/InsightSoftwareConsortium/ITK  
Build-Depends: double-conversion, libjpeg-turbo, zlib, libpng, tiff, expat, eigen3, hdf5[cpp], openjpeg  
  
Feature: vtk  
Description: Build ITKVtkGlue module.  
Build-Depends: vtk  
control: vcpkg/ports/itk/CONTROL

Source: itpp  
Version: 4.3.1-1  
Description: IT++ is a C++ library of mathematical, signal processing and communication classes and functions. Its main use is in simulation of communication systems and for performing research in the area of communications.  
control: vcpkg/ports/itpp/CONTROL

Source: ixwebsocket  
Version: 6.1.0  
Build-Depends: zlib  
Description: Lightweight WebSocket Client and Server + HTTP Client and Server  
Default-Features: ssl  
  
Feature: ssl  
Build-Depends: ixwebsocket[openssl] (!uwp&!windows&!osx), ixwebsocket[mbedtls] (windows), ixwebsocket[mbedtls] (uwp), ixwebsocket[sectransp] (osx)  
Description: Default SSL backend  
  
# SSL backends  
Feature: openssl  
Build-Depends: openssl  
Description: SSL support (OpenSSL)  
  
Feature: mbedtls  
Build-Depends: mbedtls  
Description: SSL support (mbedTLS)  
  
Feature: sectransp  
Description: SSL support (sectransp)  
control: vcpkg/ports/ixwebsocket/CONTROL

Source: jack2  
Version: 1.9.12-2  
Homepage: https://github.com/jackaudio/jack2  
Description: Cross-platform API that enables device sharing and inter-application audio routing  
  
control: vcpkg/ports/jack2/CONTROL

Source: jansson  
Version: 2.12-1  
Homepage: https://github.com/akheron/jansson  
Description: Jansson is a C library for encoding, decoding and manipulating JSON data  
control: vcpkg/ports/jansson/CONTROL

Source: jasper  
Version: 2.0.16-2  
Homepage: https://github.com/mdadams/jasper  
Description: Open source implementation of the JPEG-2000 Part-1 standard  
Build-Depends: libjpeg-turbo, opengl, freeglut  
control: vcpkg/ports/jasper/CONTROL

Source: jbig2dec  
Version: 0.16-1  
Homepage: https://github.com/ArtifexSoftware/jbig2dec  
Description: a decoder library and example utility implementing the JBIG2 bi-level image compression spec. Also known as ITU T.88 and ISO IEC 14492, and included by reference in Adobe's PDF version 1.4 and later.  
control: vcpkg/ports/jbig2dec/CONTROL

Source: jbigkit  
Version: 2.1-3  
Homepage: https://www.cl.cam.ac.uk/~mgk25/jbigkit  
Description: A software implementation of the JBIG1 data compression standard (ITU-T T.82)  
control: vcpkg/ports/jbigkit/CONTROL

Source: jemalloc  
Version: 4.3.1-4  
Homepage: https://github.com/jemalloc/jemalloc-cmake  
Description: jemalloc is a general purpose malloc(3) implementation that emphasizes fragmentation avoidance and scalable concurrency support  
Build-Depends:  
control: vcpkg/ports/jemalloc/CONTROL

Source: jinja2cpplight  
Version: 2018-05-08  
Homepage: https://github.com/hughperkins/Jinja2CppLight  
Description: (very) lightweight version of Jinja2 for C++, Lightweight templating engine for C++, based on Jinja2.  
control: vcpkg/ports/jinja2cpplight/CONTROL

Source: jsmn  
Version: 2019-04-27  
Description: A minimalistic JSON parser in C.  
control: vcpkg/ports/jsmn/CONTROL

Source: json-c  
Version: 2019-09-10  
Description: A JSON implementation in C  
Homepage: https://github.com/json-c/json-c  
control: vcpkg/ports/json-c/CONTROL

Source: json-dto  
Version: 0.2.8-2  
Description: A small header-only library for converting data between json representation and c++ structs.  
Build-Depends: rapidjson  
control: vcpkg/ports/json-dto/CONTROL

Source: json-spirit  
Version: 4.1.0-1  
Description: json parser using boost library  
Build-Depends: boost-config, boost-integer, boost-smart-ptr, boost-variant, boost-spirit  
control: vcpkg/ports/json-spirit/CONTROL

Source: json11  
Version: 2017-06-20-2  
Description: json11 is a tiny JSON library for C++11, providing JSON parsing and serialization.  
control: vcpkg/ports/json11/CONTROL

Source: json5-parser  
Version: 1.0.0-1  
Homepage: https://bitbucket.org/wlandry/json5_parser  
Description: An enhancement of the JSON Spirit C++ library to understand json5.  
Build-Depends: boost-spirit  
control: vcpkg/ports/json5-parser/CONTROL

Source: jsoncons  
Version: 0.136.0  
Description: A C++, header-only library for constructing JSON and JSON-like text and binary data formats, with JSON Pointer, JSON Patch, JSONPath, CSV, MessagePack, CBOR, BSON, UBJSON  
Homepage: https://github.com/danielaparker/jsoncons  
control: vcpkg/ports/jsoncons/CONTROL

Source: jsoncpp  
Version: 1.9.1  
Homepage: https://github.com/open-source-parsers/jsoncpp  
Description: jsoncpp is an implementation of a JSON reader and writer in C++. JSON (JavaScript Object Notation) is a lightweight data-interchange format that it is easy to parse and redeable for human.  
control: vcpkg/ports/jsoncpp/CONTROL

Source: jsonnet  
Version: 0.13.0  
Homepage: https://github.com/google/jsonnet  
Description: Jsonnet - The data templating language  
control: vcpkg/ports/jsonnet/CONTROL

Source: jwt-cpp  
Version: 2019-05-07  
Description: A header only library for creating and validating json web tokens in c++  
control: vcpkg/ports/jwt-cpp/CONTROL

Source: jxrlib  
Version: 1.1-8  
Homepage: https://github.com/4creators/jxrlib  
Description: Open source implementation of the jpegxr image format standard.  
control: vcpkg/ports/jxrlib/CONTROL

Source: kangaru  
Version: 4.2.1  
Description: A dependency injection container for C++11, C++14 and later  
control: vcpkg/ports/kangaru/CONTROL

Source: kd-soap  
Version: 1.8.0  
Description: A Qt-based client-side and server-side SOAP component  
Homepage: https://www.kdab.com/products/kd-soap  
Build-Depends: qt5-base  
control: vcpkg/ports/kd-soap/CONTROL

Source: kealib  
Version: 1.4.11-1  
Build-Depends: hdf5[cpp], zlib, szip  
Homepage: https://bitbucket.org/chchrsc/kealib  
Description: kealib is gdal model using HDF5 standard.  
  
Feature: parallel  
Description: Use parallel support for HDF5  
Build-Depends: hdf5[parallel], mpi  
control: vcpkg/ports/kealib/CONTROL

Source: keystone  
Version: 0.9.1  
Description: Lightweight multi-platform, multi-architecture assembler framework  
control: vcpkg/ports/keystone/CONTROL

Source: kf5archive  
Version: 5.58.0  
Description: File compression  
Build-Depends: ecm, qt5-base, zlib, bzip2  
control: vcpkg/ports/kf5archive/CONTROL

Source: kf5holidays  
Version: 5.58.0  
Description: Holiday calculation library  
Build-Depends: ecm, qt5-base, qt5-declarative, qt5-tools  
control: vcpkg/ports/kf5holidays/CONTROL

Source: kf5plotting  
Version: 5.58.0  
Homepage: https://api.kde.org/frameworks/kplotting/html/index.html  
Description: Lightweight plotting framework  
Build-Depends: ecm, qt5-base  
control: vcpkg/ports/kf5plotting/CONTROL

Source: kinectsdk1  
Version: 1.8-2  
Description: Kinect for Windows SDK for Kinect v1 sensor.  
control: vcpkg/ports/kinectsdk1/CONTROL

Source: kinectsdk2  
Version: 2.0-2  
Description: Kinect for Windows SDK for Kinect v2 sensor.  
control: vcpkg/ports/kinectsdk2/CONTROL

Source: kvasir-mpl  
Version: 2019-08-06  
Homepage: https://github.com/kvasir-io/mpl  
Description: This library is part of the Kvasir project. Kvasir is a collection of zero cost statically checked libraries for resource constrained systems including microcontrollers.   
  
Feature: test  
Description: Build with test  
  
control: vcpkg/ports/kvasir-mpl/CONTROL

Source: lastools  
Version: 2019-07-10  
Homepage: https://github.com/LAStools/LAStools  
Description: LAStools: award-winning software for efficient LiDAR processing (with LASzip)  
control: vcpkg/ports/lastools/CONTROL

Source: laszip  
Version: 3.4.1  
Description: LASzip - free and lossless LiDAR compression  
control: vcpkg/ports/laszip/CONTROL

Source: lazy-importer  
Version: 2019-08-10  
Description: Library for importing functions from dlls in a hidden, reverse engineer unfriendly way  
Homepage: https://github.com/JustasMasiulis/lazy_importer  
control: vcpkg/ports/lazy-importer/CONTROL

Source: lcm  
Version: 1.4.0  
Build-Depends: glib  
Homepage: https://github.com/lcm-proj/lcm  
Description: Lightweight Communications and Marshalling (LCM)  
  LCM is a set of libraries and tools for message passing and data marshalling, targeted at real-time systems where high-bandwidth and low latency are critical. It provides a publish/subscribe message passing model and automatic marshalling/unmarshalling code generation with bindings for applications in a variety of programming languages.  
control: vcpkg/ports/lcm/CONTROL

Source: lcms  
Version: 2.9  
Build-Depends:  
Homepage: https://github.com/mm2/Little-CMS  
Description: Little CMS.  
control: vcpkg/ports/lcms/CONTROL

Source: leaf  
Version: 0.2.2  
Description: Lightweight error augmentation framework   
control: vcpkg/ports/leaf/CONTROL

Source: lemon  
Version: 0  
Description: Deprecated port, use liblemon instead  
Build-Depends: liblemon  
control: vcpkg/ports/lemon/CONTROL

Source: leptonica  
Version: 1.78.0-1  
Homepage: https://github.com/DanBloomberg/leptonica  
Description: An open source library containing software that is broadly useful for image processing and image analysis applications  
Build-Depends: libjpeg-turbo, zlib, libpng, tiff, giflib, libwebp  
control: vcpkg/ports/leptonica/CONTROL

Source: lest  
Version: 1.35.1  
Description: A modern, C++11-native, single-file header-only, tiny framework for unit-tests, TDD and BDD (includes C++98 variant)  
control: vcpkg/ports/lest/CONTROL

Source: leveldb  
Version: 1.22-1  
Homepage: https://github.com/bitcoin-core/leveldb  
Description: LevelDB is a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.  
control: vcpkg/ports/leveldb/CONTROL

Source: libaiff  
Version:   5.0-1  
Homepage: https://sourceforge.net/projects/aifftools  
Description: LibAiff is an open-source library, providing C applications transparent read & write operations for Audio Interchange File Format (AIFF) files, with the goal of supporting all of its features  
control: vcpkg/ports/libaiff/CONTROL

Source: libarchive  
Version: 3.4.0  
Homepage: https://github.com/libarchive/libarchive  
Description: Library for reading and writing streaming archives  
Build-Depends: zlib  
Default-Features: bzip2, libxml2, lz4, lzma, lzo, openssl  
  
Feature: bzip2  
Build-Depends: bzip2  
Description: BZip2 support  
  
Feature: libxml2  
Build-Depends: libxml2  
Description: Libxml2 support  
  
Feature: lz4  
Build-Depends: lz4  
Description: LZ4 support  
  
Feature: lzma  
Build-Depends: liblzma  
Description: LZMA support  
  
Feature: lzo  
Build-Depends: lzo  
Description: LZO support  
  
Feature: openssl  
Build-Depends: openssl  
Description: OpenSSL support  
control: vcpkg/ports/libarchive/CONTROL

Source: libass  
Version: 0.14.0  
Build-Depends: freetype, fribidi, harfbuzz, dirent (windows)  
Description: libass is a portable subtitle renderer for the ASS/SSA (Advanced Substation Alpha/Substation Alpha) subtitle format.  
control: vcpkg/ports/libass/CONTROL

Source: libbf  
Version: 1.0.0-1  
Description: Bloom filters for C++11.  
control: vcpkg/ports/libbf/CONTROL

Source: libbson  
Version: 1.14.0-1  
Description: libbson is a library providing useful routines related to building, parsing, and iterating BSON documents.  
Homepage: https://github.com/mongodb/libbson  
control: vcpkg/ports/libbson/CONTROL

Source: libcds  
Version: 2.3.3  
Build-Depends: boost-system, boost-thread  
Homepage: https://github.com/khizmax/libcds  
Description: a collection of concurrent containers that don't require external (manual) synchronization for shared access, and safe memory reclamation (SMR) algorithms like Hazard Pointer and user-space RCU that is used as an epoch-based SMR.  
control: vcpkg/ports/libcds/CONTROL

Source: libcerf  
Version: 1.13  
Description: A self-contained numeric library that provides an efficient and accurate implementation of complex error functions, along with Dawson, Faddeeva, and Voigt functions.  
Homepage: https://jugit.fz-juelich.de/mlz/libcerf  
control: vcpkg/ports/libcerf/CONTROL

Source: libconfig  
Version: 1.7.2-1  
Homepage: https://github.com/hyperrealm/libconfig  
Description: C/C++ library for processing configuration files  
control: vcpkg/ports/libconfig/CONTROL

Source: libconfuse  
Version: 2019-07-14  
Description: Small configuration file parser library for C  
Homepage: https://github.com/martinh/libconfuse  
control: vcpkg/ports/libconfuse/CONTROL

Source: libcopp  
Version: 1.2.0  
Description: A cross-platfrom coroutine library for C++  
control: vcpkg/ports/libcopp/CONTROL

Source: libcroco  
Version: 0.6.13-1  
Description: A standalone css2 parsing and manipulation library  
Build-Depends: glib, libxml2  
control: vcpkg/ports/libcroco/CONTROL

Source: libcuckoo  
Version: 2018-12-24-1  
Description: A high-performance, concurrent hash table  
control: vcpkg/ports/libcuckoo/CONTROL

Source: libdatrie  
Version: 0.2.10-2  
Homepage: https://linux.thai.net/pub/ThaiLinux/software/libthai  
Description: implementation of double-array structure for representing trie  
Build-Depends: libiconv  
control: vcpkg/ports/libdatrie/CONTROL

Source: libdisasm  
Version: 0.23-2  
Homepage: https://sourceforge.net/projects/bastard  
Description: x86 Disassembler Library.  
control: vcpkg/ports/libdisasm/CONTROL

Source: libdshowcapture  
Version: 0.6.0-1  
Description: Free and Open Source C++11 Library for capturing DirectShow video/audio devices on windows.  
control: vcpkg/ports/libdshowcapture/CONTROL

Source: libepoxy  
Version: 1.5.3-1  
Homepage: https://github.com/anholt/libepoxy  
Description: Epoxy is a library for handling OpenGL function pointer management for you  
control: vcpkg/ports/libepoxy/CONTROL

Source: libevent  
Version: 2.1.11  
Build-Depends: openssl  
Homepage: https://github.com/libevent/libevent  
Description: An event notification library  
control: vcpkg/ports/libevent/CONTROL

Source: libexif  
Version: 0.6.21-2  
Homepage: https://libexif.github.io/  
Description: a library for parsing, editing, and saving EXIF data  
control: vcpkg/ports/libexif/CONTROL

Source: libfabric  
Version: 1.8.1  
Description: The OpenFabrics Interfaces Working Group (OFIWG) and the Libfabric open-source community are pleased to announce the release of version v1.6.2 of libfabric. See NEWS.md for the list of features and enhancements that have been added since the last release.  
Homepage: https://github.com/ofiwg/libfabric  
Build-Depends: networkdirect-sdk (windows)  
control: vcpkg/ports/libfabric/CONTROL

Source: libffi  
Version: 3.1-5  
Homepage: https://github.com/libffi/libffi  
Description: Portable, high level programming interface to various calling conventions  
control: vcpkg/ports/libffi/CONTROL

Source: libflac  
Version: 1.3.2-6  
Homepage: https://xiph.org/flac/  
Description: Library for manipulating FLAC files  
Build-Depends: libogg  
control: vcpkg/ports/libflac/CONTROL

Source: libfreenect2  
Version: 0.2.0-3  
Build-Depends: libusb, libjpeg-turbo  
Homepage: https://github.com/OpenKinect/libfreenect2  
Description: Open source drivers for the Kinect for Windows v2 device  
control: vcpkg/ports/libfreenect2/CONTROL

Source: libftdi  
Version: 0.20-1  
Build-Depends: libusb-win32  
Description: FTDI USB driver with bitbang mode (v0.20)  
control: vcpkg/ports/libftdi/CONTROL

Source: libftdi1  
Version: 1.4  
Build-Depends: libusb  
Description: FTDI USB driver with bitbang mode (v1.4)  
control: vcpkg/ports/libftdi1/CONTROL

Source: libgd  
Version: 2.2.5-3  
Homepage: https://github.com/libgd/libgd  
Description: Open source code library for the dynamic creation of images by programmers.  
Default-Features: fontconfig, freetype, jpeg, png, tiff, webp  
  
Feature: fontconfig  
Description: Support for fontconfig  
Build-Depends: fontconfig  
  
Feature: freetype  
Description: Support for freetype  
Build-Depends: freetype  
  
Feature: jpeg  
Description: Support for jpeg  
Build-Depends: libjpeg-turbo  
  
Feature: png  
Description: Support for png  
Build-Depends: libpng  
  
Feature: tiff  
Description: Support for tiff  
Build-Depends: tiff  
  
Feature: webp  
Description: Support for webp  
Build-Depends: libwebp  
control: vcpkg/ports/libgd/CONTROL

Source: libgeotiff  
Version: 1.4.2-9  
Homepage: https://download.osgeo.org/geotiff/libgeotiff  
Description: Libgeotiff is an open source library normally hosted on top of libtiff for reading, and writing GeoTIFF information tags.  
Build-Depends: tiff, proj4, zlib, libjpeg-turbo  
control: vcpkg/ports/libgeotiff/CONTROL

Source: libgit2  
Version: 0.28.3  
Homepage: https://github.com/libgit2/libgit2  
Build-Depends: openssl (!windows&&!uwp)  
Description: Git linkable library  
control: vcpkg/ports/libgit2/CONTROL

Source: libgo  
Version: 2.8-2  
Build-Depends: boost-context  
Description: The best stackful coroutine by c++11.  
control: vcpkg/ports/libgo/CONTROL

Source: libgta  
Version: 1.0.8-1  
Homepage: https://download.savannah.nongnu.org/releases/gta  
Description: Libgta is a portable library that implements the Generic Tagged Array (GTA) file format.  
Build-Depends: bzip2, zlib, liblzma  
control: vcpkg/ports/libgta/CONTROL

Source: libguarded  
Version: 2019-08-27  
Homepage: https://github.com/copperspice/libguarded  
Description: The libGuarded library is a standalone header-only library for multithreaded programming.  
control: vcpkg/ports/libguarded/CONTROL

Source: libharu  
Version: 2017-08-15-8  
Homepage: https://github.com/libharu/libharu  
Description: libharu - free PDF library  
Build-Depends: zlib, libpng  
control: vcpkg/ports/libharu/CONTROL

Source: libhydrogen  
Version: 2019-08-11  
Description: A lightweight, secure, easy-to-use crypto library suitable for constrained environments  
Homepage: https://github.com/jedisct1/libhydrogen  
control: vcpkg/ports/libhydrogen/CONTROL

Source: libiconv  
Version: 1.15-6  
Homepage: https://www.gnu.org/software/libiconv/  
Description: GNU Unicode text conversion  
control: vcpkg/ports/libiconv/CONTROL

Source: libics  
Version: 1.6.3  
Description: Reference library for ICS (Image Cytometry Standard), an open standard for writing images of any dimensionality and data type to file, together with associated information regarding the recording equipment or recorded subject.  
control: vcpkg/ports/libics/CONTROL

Source: libideviceactivation  
Version: 1.2.68-1  
Description: A library to handle the activation process of iOS devices  
Build-Depends: libimobiledevice, libxml2, curl  
control: vcpkg/ports/libideviceactivation/CONTROL

Source: libidn2  
Version: 2.2.0  
Build-Depends: libiconv  
Homepage: https://www.gnu.org/software/libidn/  
Description: GNU Libidn is an implementation of the Stringprep, Punycode and IDNA 2003 specifications. Libidn's purpose is to encode and decode internationalized domain names.  
control: vcpkg/ports/libidn2/CONTROL

Source: libimobiledevice  
Version: 1.2.76  
Description: A cross-platform protocol library to communicate with iOS devices  
Build-Depends: libplist, libusbmuxd, openssl, dirent, getopt  
control: vcpkg/ports/libimobiledevice/CONTROL

Source: libirecovery  
Version: 1.0.25-2  
Description: Library and utility to talk to iBoot/iBSS via USB on Mac OS X, Windows, and Linux  
Build-Depends: libusbmuxd, readline, getopt  
control: vcpkg/ports/libirecovery/CONTROL

Source: libjpeg-turbo  
Version: 2.0.2  
Homepage: https://github.com/libjpeg-turbo/libjpeg-turbo  
Description: libjpeg-turbo is a JPEG image codec that uses SIMD instructions (MMX, SSE2, NEON, AltiVec) to accelerate baseline JPEG compression and decompression on x86, x86-64, ARM, and PowerPC systems.  
control: vcpkg/ports/libjpeg-turbo/CONTROL

Source: libkml  
Version: 1.3.0-3  
Homepage: https://github.com/libkml/libkml  
Description: Reference implementation of OGC KML 2.2  
Build-Depends: zlib, expat, minizip[bzip2], uriparser, boost-smart-ptr  
control: vcpkg/ports/libkml/CONTROL

Source: liblas  
Version: 1.8.1-2  
Build-Depends: boost, boost-thread, boost-system, boost-iostreams, boost-filesystem, libgeotiff  
Description: A C/C++ library for reading and writing the very common LAS LiDAR format.  
  
Feature: jpeg  
Description: Support for jpeg  
Build-Depends: libjpeg-turbo  
  
Feature: zlib  
Build-Depends: zlib  
Description: Support zlib for compression  
control: vcpkg/ports/liblas/CONTROL

Source: liblbfgs  
Version: 1.10  
Homepage: http://www.chokkan.org/software/liblbfgs/  
Description:  libLBFGS: a library of Limited-memory Broyden-Fletcher-Goldfarb-Shanno (L-BFGS)   
control: vcpkg/ports/liblbfgs/CONTROL

Source: liblemon  
Version: 2019-06-13  
Description: Library for Efficient Modeling and Optimization in Networks  
control: vcpkg/ports/liblemon/CONTROL

Source: liblinear  
Version: 230  
Description: A Library for Large Linear Classification  
control: vcpkg/ports/liblinear/CONTROL

Source: liblo  
Version: 0.30  
Homepage: https://github.com/radarsat1/liblo  
Description: liblo is an implementation of the Open Sound Control protocol for POSIX systems  
control: vcpkg/ports/liblo/CONTROL

Source: liblsl  
Version: 1.13.0-b11-1  
Description: C++ lsl library for multi-modal time-synched data transmission over the local network  
control: vcpkg/ports/liblsl/CONTROL

Source: liblzma  
Version: 5.2.4-2  
Homepage: https://github.com/xz-mirror/xz  
Description: Compression library with an API similar to that of zlib.  
control: vcpkg/ports/liblzma/CONTROL

Source: libmad  
Version: 0.15.1-3  
Description: high-quality MPEG audio decoder  
control: vcpkg/ports/libmad/CONTROL

Source: libmariadb  
Version: 3.0.10-4  
Homepage: https://github.com/MariaDB/mariadb-connector-c  
Description: MariaDB Connector/C is used to connect C/C++ applications to MariaDB and MySQL databases  
control: vcpkg/ports/libmariadb/CONTROL

Source: libmaxminddb  
Version: 1.3.2-2  
Description: C library for the MaxMind DB file format  
control: vcpkg/ports/libmaxminddb/CONTROL

Source: libmicrohttpd  
Version: 0.9.63  
Homepage: https://www.gnu.org/software/libmicrohttpd/  
Description: GNU libmicrohttpd is a small C library that is supposed to make it easy to run an HTTP server as part of another application  
control: vcpkg/ports/libmicrohttpd/CONTROL

Source: libmikmod  
Version: 3.3.11.1-5  
Homepage: https://sourceforge.net/projects/mikmod/  
Description: Mikmod is a module player and library supporting many formats, including mod, s3m, it, and xm.  
Build-Depends: openal-soft  
control: vcpkg/ports/libmikmod/CONTROL

Source: libmodbus  
Version: 3.1.6  
Description: libmodbus is a free software library to send/receive data with a device which respects the Modbus protocol  
control: vcpkg/ports/libmodbus/CONTROL

Source: libmodplug  
Version: 0.8.9.0-4  
Homepage: https://github.com/Konstanty/libmodplug  
Description: The ModPlug mod file playing library.  
control: vcpkg/ports/libmodplug/CONTROL

Source: libmorton  
Version: 0.2  
Description: header-only library for encoding/decoding Morton codes in/from 2D/3D coordinates  
control: vcpkg/ports/libmorton/CONTROL

Source: libmspack  
Version: 0.10.1-1  
Build-Depends:  
Homepage: https://www.cabextract.org.uk/libmspack  
Description: libmspack is a portable library for some loosely related Microsoft compression formats.  
control: vcpkg/ports/libmspack/CONTROL

Source: libmupdf  
Version: 1.15.0-1  
Build-Depends: freetype, libjpeg-turbo, harfbuzz, zlib, curl, glfw3, openjpeg, jbig2dec  
Homepage: https://github.com/ArtifexSoftware/mupdf  
Description: a lightweight PDF, XPS, and E-book library  
control: vcpkg/ports/libmupdf/CONTROL

Source: libmysql  
Version: 8.0.4-4  
Homepage: https://github.com/mysql/mysql-server  
Build-Depends: boost-algorithm, boost-geometry, boost-optional, boost-functional, boost-graph, openssl, icu, libevent, liblzma, lz4, zlib  
Description: A MySQL client library for C development.  
control: vcpkg/ports/libmysql/CONTROL

Source: libnice  
Version: 0.1.15-1  
Homepage: https://nice.freedesktop.org  
Description: Libnice is an implementation of the IETF's Interactive Connectivity Establishment (ICE) standard (RFC 5245) and the Session Traversal Utilities for NAT (STUN) standard (RFC 5389).  
Build-Depends: glib, openssl  
control: vcpkg/ports/libnice/CONTROL

Source: libnoise  
Version: 1.0.0  
Description: A general-purpose library that generates three-dimensional coherent noise. Useful for terrain generation and procedural texture generation. Uses a broad number of techniques (Perlin noise, ridged multifractal, etc.) and combinations of those techniques.  
control: vcpkg/ports/libnoise/CONTROL

Source: libodb  
Version: 2.4.0-6  
Homepage: https://www.codesynthesis.com/products/odb/  
Description: ODB library, base runtime for the ODB ORM solution  
control: vcpkg/ports/libodb/CONTROL

Source: libodb-boost  
Version: 2.4.0-3  
Description: Description: Boost support for the ODB ORM library  
Build-Depends: libodb  
control: vcpkg/ports/libodb-boost/CONTROL

Source: libodb-mysql  
Version: 2.4.0-4  
Homepage: https://www.codesynthesis.com/products/odb/  
Description: MySQL support for the ODB ORM library  
Build-Depends: libodb, libmysql  
control: vcpkg/ports/libodb-mysql/CONTROL

Source: libodb-pgsql  
Version: 2.4.0-3  
Homepage: https://www.codesynthesis.com/products/odb/  
Description: Description: PostgreSQL support for the ODB ORM library  
Build-Depends: libodb, libpq  
control: vcpkg/ports/libodb-pgsql/CONTROL

Source: libodb-sqlite  
Version: 2.4.0-5  
Homepage: https://www.codesynthesis.com/products/odb/  
Description: Sqlite support for the ODB ORM library  
Build-Depends: libodb, sqlite3  
control: vcpkg/ports/libodb-sqlite/CONTROL

Source: libogg  
Version: 1.3.4  
Description: Ogg is a multimedia container format, and the native file and stream format for the Xiph.org multimedia codecs.  
Homepage: https://github.com/xiph/ogg  
control: vcpkg/ports/libogg/CONTROL

Source: libopenmpt  
Version: 2017-01-28-cf2390140  
Homepage: https://github.com/OpenMPT/openmpt  
Description: a library to render tracker music  
Build-Depends: zlib, mpg123, libogg, libvorbis, portaudio, libflac  
control: vcpkg/ports/libopenmpt/CONTROL

Source: libopusenc  
Version: 0.2.1  
Homepage: https://github.com/xiph/libopusenc  
Description: Library for encoding .opus audio files and live streams.  
Build-Depends: opus  
control: vcpkg/ports/libopusenc/CONTROL

Source: libosip2  
Version: 5.1.0  
Homepage: https://www.gnu.org/software/osip/  
Description: oSIP is an LGPL implementation of SIP. It's stable, portable, flexible and compliant! -may be more-! It is used mostly with eXosip2 stack (GPL) which provides simpler API for User-Agent implementation.  
control: vcpkg/ports/libosip2/CONTROL

Source: libp7-baical  
Version: 4.4-4  
Homepage: https://baical.net/  
Description: P7 is a library for high-speed sending telemetry & trace data from application  
control: vcpkg/ports/libp7-baical/CONTROL

Source: libp7client  
Version: 5.2-1  
Description: Open source, cross-platform, fastest library for sending logs, telemetry & trace data from your application.  
control: vcpkg/ports/libp7client/CONTROL

Source: libpcap  
Version: 1.9.0  
Description: A portable C/C++ library for network traffic capture  
control: vcpkg/ports/libpcap/CONTROL

Source: libpff  
Version: 2018-07-14-1  
Build-Depends: zlib  
Description: Library and tools to access the Personal Folder File (PFF) and the Offline Folder File (OFF) format.  
control: vcpkg/ports/libpff/CONTROL

Source: libplist  
Version: 1.2.77  
Description: A library to handle Apple Property List format in binary or XML   
control: vcpkg/ports/libplist/CONTROL

Source: libpmemobj-cpp  
Version: 1.7  
#Build-Depends: pmdk  
Description: C++ bindings for libpmemobj (https://github.com/pmem/pmdk).  
control: vcpkg/ports/libpmemobj-cpp/CONTROL

Source: libpng  
Version: 1.6.37-4  
Build-Depends: zlib  
Homepage: https://github.com/glennrp/libpng  
Description: libpng is a library implementing an interface for reading and writing PNG (Portable Network Graphics) format files.  
control: vcpkg/ports/libpng/CONTROL

Source: libpng-apng  
Version: 1.6.37  
Build-Depends: zlib  
Homepage: https://github.com/glennrp/libpng  
Description: libpng-apng is a library implementing an interface for reading and writing (A)PNG ((Animated) Portable Network Graphics) format files. This is backward compatible with the regular libpng, both in library usage and format.  
control: vcpkg/ports/libpng-apng/CONTROL

Source: libpopt  
Version: 1.16-10~vcpkg1-1  
Description: Library for parsing command line parameters  
control: vcpkg/ports/libpopt/CONTROL

Source: libpq  
Version: 9.6.1-8  
Homepage: https://www.postgresql.org/  
Description: The official database access API of postgresql  
Build-Depends: openssl, zlib (linux)  
control: vcpkg/ports/libpq/CONTROL

Source: libpqxx  
Version: 6.4.5  
Homepage: https://github.com/jtv/libpqxx  
Description: The official C++ client API for PostgreSQL  
Build-Depends: libpq  
control: vcpkg/ports/libpqxx/CONTROL

Source: libqglviewer  
Version: 2.7.0-2  
Description: libQGLViewer is an open source C++ library based on Qt that eases the creation of OpenGL 3D viewers.  
Build-Depends: qt5-base  
control: vcpkg/ports/libqglviewer/CONTROL

Source: libqrencode  
Version: 4.0.2-1  
Build-Depends: libpng, libiconv  
Homepage: https://github.com/fukuchi/libqrencode  
Description: libqrencode - a fast and compact QR Code encoding library  
  
Feature: tool  
Description: Build qrencode tool  
Build-Depends: getopt (windows)    
control: vcpkg/ports/libqrencode/CONTROL

Source: librabbitmq  
Version: 0.9.0-1  
Build-Depends: openssl  
Homepage: https://github.com/alanxz/rabbitmq-c  
Description: A C-language AMQP client library for use with v2.0+ of the RabbitMQ broker.  
control: vcpkg/ports/librabbitmq/CONTROL

Source: libraqm  
Version: 0.7.0  
Description:  A library for complex text layout   
Build-Depends: freetype, harfbuzz, fribidi  
control: vcpkg/ports/libraqm/CONTROL

Source: libraw  
Version: 201903-1  
Build-Depends: lcms, jasper  
Homepage: https://www.libraw.org  
Description: raw image decoder library  
control: vcpkg/ports/libraw/CONTROL

Source: librdkafka  
Version: 1.2.0-2  
Description: The Apache Kafka C/C++ library  
Homepage: https://github.com/edenhill/librdkafka  
  
Feature: lz4  
Description: Enable external LZ4 library support   
Build-Depends: lz4  
  
Feature: ssl  
Description: Build with OpenSSL  
Build-Depends: openssl  
  
Feature: zlib  
Description: Build with zlib  
Build-Depends: zlib  
  
Feature: zstd  
Description: Build with zstd  
Build-Depends: zstd  
  
Feature: snappy  
Description: Build with snappy  
control: vcpkg/ports/librdkafka/CONTROL

Source: libressl  
Version: 2.9.1-2  
Description: LibreSSL is a version of the TLS/crypto stack forked from OpenSSL in 2014, with goals of modernizing the codebase, improving security, and applying best practice development processes.  
  
Feature: tools  
Description: Build openssl and ocspcheck executables  
control: vcpkg/ports/libressl/CONTROL

Source: librsvg  
Version: 2.40.20  
Description: A small library to render Scalable Vector Graphics (SVG)  
Build-Depends: cairo, pango, gdk-pixbuf, libcroco  
control: vcpkg/ports/librsvg/CONTROL

Source: librsync  
Version: 2.0.2-1  
Description: librsync is a library for calculating and applying network deltas, with an interface designed to ease integration into diverse network applications.  
control: vcpkg/ports/librsync/CONTROL

Source: librtmp  
Version: 2.4-1  
Build-Depends: zlib, openssl  
Homepage: https://rtmpdump.mplayerhq.hu  
Description: RTMPDump Real-Time Messaging Protocol API  
control: vcpkg/ports/librtmp/CONTROL

Source: libsamplerate  
Version: 0.1.9.0-1  
Homepage: https://www.mega-nerd.com/SRC  
Description: Sample Rate Converter for audio  
control: vcpkg/ports/libsamplerate/CONTROL

Source: libsigcpp  
Version: 2.10-1  
Description: Typesafe callback framework for C++  
control: vcpkg/ports/libsigcpp/CONTROL

Source: libsndfile  
Version: 1.0.29-8  
Description: Library to read, write and manipulate many soundfile types. Authored by Eric de Castro Lopo  
Homepage: https://github.com/erikd/libsndfile  
Default-Features: external-libs  
  
Feature: external-libs  
Description: Support Ogg Vorbis and FLAC audio files  
Build-Depends: libogg, libflac, libvorbis  
control: vcpkg/ports/libsndfile/CONTROL

Source: libsodium  
Version: 1.0.18-1  
Description: A modern and easy-to-use crypto library  
Homepage: https://github.com/jedisct1/libsodium  
control: vcpkg/ports/libsodium/CONTROL

Source: libsoundio  
Version: 2.0.0  
Description: libsoundio is C library providing cross-platform audio input and output.  
Homepage: http://libsound.io/  
control: vcpkg/ports/libsoundio/CONTROL

Source: libspatialindex  
Version: 1.9.0  
Homepage: http://libspatialindex.github.com  
Description: C++ implementation of R*-tree, an MVR-tree and a TPR-tree with C API.  
Build-Depends: zlib  
  
control: vcpkg/ports/libspatialindex/CONTROL

Source: libspatialite  
Version: 4.3.0a-4  
Homepage: https://www.gaia-gis.it/gaia-sins/libspatialite-sources  
Description: SpatiaLite is an open source library intended to extend the SQLite core to support fully fledged Spatial SQL capabilities.  
Build-Depends: libxml2, sqlite3, geos, proj4, zlib, freexl, libiconv  
  
control: vcpkg/ports/libspatialite/CONTROL

Source: libsquish  
Version: 1.15-2  
Homepage: https://sourceforge.net/projects/libsquish  
Description: Open source DXT compression library.  
control: vcpkg/ports/libsquish/CONTROL

Source: libsrtp  
Version: 2.2.0  
Description: This package provides an implementation of the Secure Real-time Transport Protocol (SRTP), the Universal Security Transform (UST), and a supporting cryptographic kernel.  
control: vcpkg/ports/libsrtp/CONTROL

Source: libssh  
Version: 0.7.6-1  
Homepage: https://www.libssh.org/  
Description: libssh is a multiplatform C library implementing the SSHv2 and SSHv1 protocol on client and server side  
Build-Depends: openssl  
  
Feature: zlib  
Description: libssh with zlib  
Build-Depends: zlib  
control: vcpkg/ports/libssh/CONTROL

Source: libssh2  
Version: 1.9.0  
Build-Depends: zlib, openssl  
Homepage: https://www.libssh2.org  
Description: The SSH library  
control: vcpkg/ports/libssh2/CONTROL

Source: libstemmer  
Version: 2017-9-4  
Homepage: https://snowball.tartarus.org/  
Description: Snowball is a small string processing language designed for creating stemming algorithms for use in Information Retrieval  
control: vcpkg/ports/libstemmer/CONTROL

Source: libstk  
Version: 4.6.1  
Description: The Synthesis ToolKit in C++ (STK) is a set of open source audio signal processing and algorithmic synthesis classes written in the C++ programming language.   
control: vcpkg/ports/libstk/CONTROL

Source: libsvm  
Version: 323  
Description: A library for Support Vector Machines  
Homepage: https://www.csie.ntu.edu.tw/~cjlin/libsvm/  
  
Feature: tools  
Description: Build libsvm tools  
control: vcpkg/ports/libsvm/CONTROL

Source: libtheora  
Version: 1.2.0alpha1-20170719~vcpkg1-3  
Homepage: https://github.com/xiph/theora  
Description: Theora is a free and open video compression format from the Xiph.org Foundation.  
Build-Depends: libogg  
control: vcpkg/ports/libtheora/CONTROL

Source: libtins  
Version: 4.2  
Description: High-level, multiplatform C++ network packet sniffing and crafting library  
Build-Depends: winpcap (windows), boost-icl, boost-any  
control: vcpkg/ports/libtins/CONTROL

Source: libtorrent  
Version: 1.2.1-bcb26fd6  
Homepage: https://github.com/arvidn/libtorrent  
Description: An efficient feature complete C++ BitTorrent implementation   
Build-Depends: openssl, boost-system, boost-date-time, boost-chrono, boost-random, boost-asio, boost-crc, boost-config, boost-iterator, boost-scope-exit, boost-multiprecision  
control: vcpkg/ports/libtorrent/CONTROL

Source: libu2f-server  
Version: 1.1.0  
Build-Depends: openssl, json-c  
Description: Yubico Universal 2nd Factor (U2F) Server C Library  
control: vcpkg/ports/libu2f-server/CONTROL

Source: libudis86  
Version: 2018-01-28-56ff6c87  
Homepage: https://github.com/vmt/udis86  
Description: Disassembler Library for x86 and x86-64   
control: vcpkg/ports/libudis86/CONTROL

Source: libui  
Version: 2018-11-03-1  
Description: Simple and portable (but not inflexible) native GUI library in C.  
control: vcpkg/ports/libui/CONTROL

Source: libunibreak  
Version: 4.2  
Homepage: https://github.com/adah1972/libunibreak  
Description: an implementation of the line breaking and word breaking algorithms as described in [Unicode Standard Annex 14] 1 and [Unicode Standard Annex 29] 2. Check the project's [home page] 3 for up-to-date information.  
control: vcpkg/ports/libunibreak/CONTROL

Source: libusb  
Version: 1.0.22-4  
Homepage: https://github.com/libusb/libusb  
Description: a cross-platform library to access USB devices  
control: vcpkg/ports/libusb/CONTROL

Source: libusb-win32  
Version: 1.2.6.0-2  
Homepage: https://sourceforge.net/projects/libusb-win32  
Description: Allows user space applications to access many USB device on Windows.  
control: vcpkg/ports/libusb-win32/CONTROL

Source: libusbmuxd  
Version: 1.2.77  
Description: A client library to multiplex connections from and to iOS devices  
Build-Depends: libplist  
control: vcpkg/ports/libusbmuxd/CONTROL

Source: libuuid  
Version: 1.0.3-2  
Description: Universally unique id library  
control: vcpkg/ports/libuuid/CONTROL

Source: libuv  
Version: 1.30.1  
Homepage: https://github.com/libuv/libuv  
Description: libuv is a multi-platform support library with a focus on asynchronous I/O.  
control: vcpkg/ports/libuv/CONTROL

Source: libvorbis  
Version: 1.3.6-9eadecc-3  
Homepage: https://github.com/xiph/vorbis  
Description: Ogg Vorbis is a fully open, non-proprietary, patent-and-royalty-free, general-purpose compressed audio format.  
Build-Depends: libogg  
control: vcpkg/ports/libvorbis/CONTROL

Source: libvpx  
Version: 1.8.1  
Homepage: https://github.com/webmproject/libvpx  
Description: The reference software implementation for the video coding formats VP8 and VP9.  
control: vcpkg/ports/libvpx/CONTROL

Source: libwebm  
Version: 1.0.0.27-5  
Homepage: https://github.com/webmproject/libwebm  
Description: WebM File Parser  
control: vcpkg/ports/libwebm/CONTROL

Source: libwebp  
Version: 1.0.2-7  
Homepage: https://github.com/webmproject/libwebp  
Description: Lossy compression of digital photographic images.  
Build-Depends: opengl  
  
Feature: all  
Description: enable all webp features  
Build-Depends: giflib, libjpeg-turbo, zlib, libpng, tiff, freeglut (!osx), sdl1 (windows)  
control: vcpkg/ports/libwebp/CONTROL

Source: libwebsockets  
Version: 3.2.0  
Build-Depends: zlib, openssl  
Homepage: https://github.com/warmcat/libwebsockets  
Description: Libwebsockets is a lightweight pure C library built to use minimal CPU and memory resources, and provide fast throughput in both directions as client or server.  
control: vcpkg/ports/libwebsockets/CONTROL

Source: libxlsxwriter  
Version: 0.8.7-1  
Description: Libxlsxwriter is a C library that can be used to write text, numbers, formulas and hyperlinks to multiple worksheets in an Excel 2007+ XLSX file.  
Build-Depends: zlib  
control: vcpkg/ports/libxlsxwriter/CONTROL

Source: libxml2  
Version: 2.9.9-4  
Homepage: https://xmlsoft.org/  
Description: Libxml2 is the XML C parser and toolkit developed for the Gnome project (but usable outside of the Gnome platform)  
Build-Depends: zlib, libiconv, liblzma  
control: vcpkg/ports/libxml2/CONTROL

Source: libxmlpp  
Version: 2.40.1-3  
Description: a C++ wrapper for the libxml XML parser library.  
Build-Depends: libxml2, glibmm  
control: vcpkg/ports/libxmlpp/CONTROL

Source: libxmp-lite  
Version: 4.4.1-1  
Homepage: https://sourceforge.net/projects/xmp/  
Description: Lightweight version of libxmp that supports MOD, S3M, XM and IT modules.  
control: vcpkg/ports/libxmp-lite/CONTROL

Source: libxslt  
Version: 1.1.33-2  
Homepage: http://xmlsoft.org/XSLT/  
Description: Libxslt is a XSLT library implemented in C for XSLT 1.0 and most of EXSLT  
Build-Depends: libxml2, liblzma  
control: vcpkg/ports/libxslt/CONTROL

Source: libyaml  
Version: 0.2.2-2  
Description: A C library for parsing and emitting YAML.  
control: vcpkg/ports/libyaml/CONTROL

Source: libyuv  
Version: fec9121  
Build-Depends: libjpeg-turbo  
Description: libyuv is an open source project that includes YUV scaling and conversion functionality.  
control: vcpkg/ports/libyuv/CONTROL

Source: libzen  
Version: 0.4.37  
Description: ZenLib is a C++ utility library for easiest cross-platform development  
control: vcpkg/ports/libzen/CONTROL

Source: libzip  
Version: rel-1-5-2  
Homepage: https://github.com/nih-at/libzip  
Build-Depends: zlib  
Default-Features: openssl, bzip2  
Description: A library for reading, creating, and modifying zip archives.  
  
Feature: bzip2  
Build-Depends: bzip2  
Description: Support bzip2-compressed zip archives  
  
Feature: openssl  
Build-Depends: openssl  
Description: AES (encryption) support using OpenSSL  
control: vcpkg/ports/libzip/CONTROL

Source: libzippp  
Version: 2019-07-22  
Description: Simple basic C++ wrapper around the libzip library. It is meant to be a portable and easy-to-use library for ZIP handling  
Build-Depends: zlib, libzip[bzip2]  
control: vcpkg/ports/libzippp/CONTROL

Source: linalg  
Version: 2.1  
Description: linalg.h is a single header public domain linear algebra library for C++11  
control: vcpkg/ports/linalg/CONTROL

Source: linenoise-ng  
Version: 4754bee2d8eb3-1  
Description: A small, portable GNU readline replacement for Linux, Windows and MacOS which is capable of handling UTF-8 characters.  
control: vcpkg/ports/linenoise-ng/CONTROL

Source: live555  
Version: latest  
Homepage: https://www.live555.com/liveMedia  
Description: A complete RTSP server application  
control: vcpkg/ports/live555/CONTROL

Source: llgl  
Version: 2019-08-15  
Homepage: https://github.com/LukasBanana/LLGL  
Description: Low Level Graphics Library (LLGL) is a thin abstraction layer for the modern graphics APIs OpenGL, Direct3D, Vulkan, and Metal.  
  
Feature: opengl  
Description: Support for opengl  
  
Feature: direct3d11  
Description: Support for direct3d11  
control: vcpkg/ports/llgl/CONTROL

Source: llvm  
Version: 8.0.0-2  
Homepage: https://llvm.org/  
Description: The LLVM Compiler Infrastructure  
Build-Depends: atlmfc (windows)  
control: vcpkg/ports/llvm/CONTROL

Source: lmdb  
Version: 0.9.23-2  
Homepage: https://github.com/LMDB/lmdb  
Description: LMDB is an extraordinarily fast, memory-efficient database  
control: vcpkg/ports/lmdb/CONTROL

Source: lodepng  
Version: 2018-09-18-2  
Homepage: https://github.com/lvandeve/lodepng  
Description: PNG encoder and decoder in C and C++  
control: vcpkg/ports/lodepng/CONTROL

Source: log4cplus  
Version: 2.0.4-1  
Homepage: https://github.com/log4cplus/log4cplus  
Description: A simple to use C++ logging API providing thread--safe, flexible, and arbitrarily granular control over log management and configuration  
Build-Depends: catch  
control: vcpkg/ports/log4cplus/CONTROL

Source: log4cpp  
Version: 2.9.1-1  
Homepage: https://github.com/orocos-toolchain/log4cpp  
Description: Log4cpp is library of C++ classes for flexible logging to files, syslog, IDSA and other destinations. It is modeled after the Log4j Java library, staying as close to their API as is reasonable.  
  
control: vcpkg/ports/log4cpp/CONTROL

Source: loguru  
Version: v2.0.0  
Description: A lightweight and flexible C++ logging library  
Build-Depends:  
control: vcpkg/ports/loguru/CONTROL

Source: lpeg  
Version: 1.0.1-3  
Homepage: https://www.inf.puc-rio.br/~roberto/lpeg  
Description: LPeg is a pattern-matching library for Lua, based on Parsing Expression Grammars (PEGs).  
Build-Depends: lua  
control: vcpkg/ports/lpeg/CONTROL

Source: lua  
Version: 5.3.5-2  
Homepage: https://www.lua.org  
Description: a powerful, fast, lightweight, embeddable scripting language  
  
Feature: cpp  
Description: Builds lua for C++ linkage.  
control: vcpkg/ports/lua/CONTROL

Source: luabridge  
Version: 2.3.2  
Description: A lightweight, dependency-free library for binding Lua to C++  
control: vcpkg/ports/luabridge/CONTROL

Source: luafilesystem  
Version: 1.7.0.2  
Homepage: https://github.com/keplerproject/luafilesystem  
Description: LuaFileSystem is a Lua library developed to complement the set of functions related to file systems offered by the standard Lua distribution.  
Build-Depends: lua  
control: vcpkg/ports/luafilesystem/CONTROL

Source: luajit  
Version: 2.0.5-2  
Homepage: https://github.com/LuaJIT/LuaJIT  
Description: LuaJIT is a Just-In-Time (JIT) compiler for the Lua programming language.  
control: vcpkg/ports/luajit/CONTROL

Source: luasocket  
Version: 2019-05-07  
Homepage: https://github.com/diegonehab/luasocket  
Description: LuaSocket is a Lua extension library that is composed by two parts: a C core that provides support for the TCP and UDP transport layers, and a set of Lua modules that add support for functionality commonly needed by applications that deal with the Internet.  
Build-Depends: lua  
control: vcpkg/ports/luasocket/CONTROL

Source: lz4  
Version: 1.9.2  
Homepage: https://github.com/lz4/lz4  
Description: Lossless compression algorithm, providing compression speed at 400 MB/s per core.  
Build-Depends: xxhash  
control: vcpkg/ports/lz4/CONTROL

Source: lzfse  
Version: 1.0-1  
Homepage: https://github.com/lzfse/lzfse  
Description: Lempel-Ziv style data compressor using Finite State Entropy coding.  
control: vcpkg/ports/lzfse/CONTROL

Source: lzo  
Version: 2.10-3  
Homepage: https://www.oberhumer.com/opensource/lzo/  
Description: Lossless data compression library  
control: vcpkg/ports/lzo/CONTROL

Source: magic-enum  
Version: 0.6.1  
Description: Header-only C++17 library provides static reflection for enums, work with any enum type without any macro or boilerplate code.  
control: vcpkg/ports/magic-enum/CONTROL

Source: magic-get  
Version: 2019-09-02  
Homepage: https://github.com/apolukhin/magic_get  
Description: This C++14 library is meant for accessing structure elements by index and providing other std::tuple like methods for user defined types without any macro or boilerplate code.  
control: vcpkg/ports/magic-get/CONTROL

Source: magnum  
Version: 2019.01-1  
Build-Depends: corrade[utility]  
Description: C++11/C++14 graphics middleware for games and data visualization   
Homepage: https://magnum.graphics/  
Default-Features: anyimageimporter, anyaudioimporter, anyimageconverter, anysceneimporter, debugtools, gl, meshtools, primitives, scenegraph, shaders, text, texturetools, trade, sdl2application  
  
Feature: al-info  
Description: magnum-al-info utility  
Build-Depends: magnum[audio]  
  
Feature: anyimageimporter  
Description: AnyImageImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: anyaudioimporter  
Description: AnyAudioImporter plugin  
Build-Depends: magnum[audio], corrade[pluginmanager]  
  
Feature: anyimageconverter  
Description: AnyImageConverter plugin  
Build-Depends: magnum[trade]  
  
Feature: anysceneimporter  
Description: AnySceneImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: audio  
Description: Audio library  
Build-Depends: openal-soft  
  
Feature: debugtools  
Description: DebugTools library  
  
Feature: distancefieldconverter  
Description: magnum-distancefieldconverter utility  
Build-Depends: magnum[texturetools], magnum[gl]  
  
Feature: fontconverter  
Description: magnum-fontconverter utility  
Build-Depends: magnum[text], magnum[gl]  
  
Feature: gl  
Description: GL library  
  
Feature: gl-info  
Description: gl-info utility  
Build-Depends: magnum[gl]  
  
Feature: glfwapplication  
Description: GlfwApplication library  
Build-Depends: glfw3  
  
Feature: imageconverter  
Description: magnum-imageconverter utility  
Build-Depends: magnum[trade]  
  
Feature: magnumfont  
Description: MagnumFont plugin  
Build-Depends: magnum[text]  
  
Feature: magnumfontconverter  
Description: MagnumFontConverter plugin  
Build-Depends: magnum[text], magnum[tgaimageconverter]  
  
Feature: meshtools  
Description: MeshTools library  
Build-Depends: magnum[trade]  
  
Feature: objimporter  
Description: ObjImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: tgaimageconverter  
Description: TgaImageConverter plugin  
Build-Depends: magnum[trade]  
  
Feature: opengltester  
Description: OpenGLTester library  
Build-Depends: corrade[testsuite], magnum[gl]  
  
Feature: primitives  
Description: Primitives library  
Build-Depends: magnum[trade]  
  
Feature: sdl2application  
Description: Sdl2Application library  
Build-Depends: sdl2  
  
Feature: scenegraph  
Description: SceneGraph library  
  
Feature: shaders  
Description: Shaders library  
Build-Depends: magnum[gl]  
  
Feature: text  
Description: Text library  
Build-Depends: magnum[texturetools], magnum[gl], corrade[pluginmanager]  
  
Feature: texturetools  
Description: TextureTools library  
  
Feature: tgaimporter  
Description: TgaImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: trade  
Description: Trade library  
Build-Depends: corrade[pluginmanager]  
  
Feature: wavaudioimporter  
Description: WavAudioImporter plugin  
Build-Depends: magnum[audio]  
  
Feature: windowlesswglapplication  
Description: WindowlessWglApplication library  
Build-Depends: magnum[gl]  
  
Feature: eglcontext  
Description: EglContext library  
Build-Depends: magnum[gl]  
  
Feature: cglcontext  
Description: CglContext library  
Build-Depends: magnum[gl]  
  
Feature: glxcontext  
Description: GlxContext library  
Build-Depends: magnum[gl]  
  
Feature: wglcontext  
Description: WglContext library  
Build-Depends: magnum[gl]  
  
Feature: windowlesseglapplication  
Description: WindowlessEglApplication library  
Build-Depends: magnum[gl]  
  
Feature: eglcontext  
Description: EglContext library  
Build-Depends: magnum[gl]  
  
Feature: windowlessglxapplication  
Description: WindowlessGlxApplication library  
Build-Depends: magnum[gl]  
  
Feature: glxcontext  
Description: GlxContext library  
Build-Depends: magnum[gl]  
control: vcpkg/ports/magnum/CONTROL

Source: magnum-extras  
Version: 2019.01-2  
Build-Depends: magnum[core]  
Description: Extras for magnum, C++11/C++14 graphics middleware for games and data visualization  
Homepage: https://magnum.graphics/  
  
Feature: ui  
Description: Ui library  
Build-Depends: corrade[interconnect], magnum[text]  
control: vcpkg/ports/magnum-extras/CONTROL

Source: magnum-integration  
Version: 2019.01-2  
Build-Depends: magnum[core]  
Description: Integrations for magnum, C++11/C++14 graphics middleware for games and data visualization  
Homepage: https://magnum.graphics/  
  
Feature: bullet  
Description: BulletIntegration library  
Build-Depends: bullet3  
  
Feature: glm  
Description: GlmIntegration library  
Build-Depends: glm  
  
Feature: imgui  
Description: ImGuiIntegration library  
Build-Depends: imgui  
#Feature: ovr  
#Description: OvrIntegration library  
#Build-Depends: ovrsdk  
#Feature: dart  
#Description: DartIntegration library  
#Build-Depends: dart  
control: vcpkg/ports/magnum-integration/CONTROL

Source: magnum-plugins  
Version: 2019.01-1  
Build-Depends: magnum[core]  
Description: Plugins for magnum, C++11/C++14 graphics middleware for games and data visualization  
Homepage: https://magnum.graphics/  
Default-Features: ddsimporter, miniexrimageconverter, opengeximporter, stanfordimporter, stbimageconverter, stbimageimporter  
  
Feature: assimpimporter  
Description: AssimpImporter plugin  
Build-Depends: assimp, magnum[anyimageimporter], magnum[trade]  
  
Feature: openddl  
Description: OpenDdl library  
  
Feature: ddsimporter  
Description: DdsImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: devilimageimporter  
Description: DevIlImageImporter plugin  
Build-Depends: devil, magnum[trade]  
  
Feature: drflacaudioimporter  
Description: DrFlacAudioImporter plugin  
Build-Depends: magnum[audio]  
  
Feature: drwavaudioimporter  
Description: DrWavAudioImporter plugin  
Build-Depends: magnum[audio]  
#Feature: faad2audioimporter  
#Description: Faad2AudioImporter plugin  
#Build-Depends: magnum[audio], faad2  
  
Feature: freetypefont  
Description: FreeTypeFont plugin  
Build-Depends: freetype, magnum[text]  
  
Feature: harfbuzzfont  
Description: HarfBuzzFont plugin  
Build-Depends: harfbuzz, magnum-plugins[freetypefont]  
  
Feature: jpegimporter  
Description: JpegImporter plugin  
Build-Depends: libjpeg-turbo, magnum[trade]  
  
Feature: jpegimageconverter  
Description: JpegImageConverter plugin  
Build-Depends: libjpeg-turbo, magnum[trade]  
  
Feature: miniexrimageconverter  
Description: MiniExrImageConverter plugin  
Build-Depends: magnum[trade]  
  
Feature: opengeximporter  
Description: OpenGexImporter plugin  
Build-Depends: magnum[anyimageimporter], magnum[trade], magnum-plugins[openddl]  
  
Feature: pngimageconverter  
Description: PngImageConverter plugin  
Build-Depends: libpng, magnum[trade]  
  
Feature: pngimporter  
Description: PngImporter plugin  
Build-Depends: libpng, magnum[trade]  
  
Feature: stanfordimporter  
Description: StanfordImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: stbimageconverter  
Description: StbImageConverter plugin  
Build-Depends: magnum[trade]  
  
Feature: stbimageimporter  
Description: StbImageImporter plugin  
Build-Depends: magnum[trade]  
  
Feature: stbtruetypefont  
Description: StbTrueTypeFont plugin  
Build-Depends: magnum[text]  
  
Feature: stbvorbisaudioimporter  
Description: StbVorbisAudioImporter plugin  
Build-Depends: magnum[audio]  
  
Feature: tinygltfimporter  
Description: TinyGltfImporter plugin  
Build-Depends: magnum[anyimageimporter], magnum-plugins[stbimageimporter], magnum[trade]  
control: vcpkg/ports/magnum-plugins/CONTROL

Source: mapbox-variant  
Version: 1.1.6-0f734f0-1  
Description: C++11/C++14 Variant  
control: vcpkg/ports/mapbox-variant/CONTROL

Source: marl  
Version: 2019-09-13  
Description: A hybrid thread/fiber task scheduler written in C++ 11  
Homepage: https://github.com/google/marl  
control: vcpkg/ports/marl/CONTROL

Source: mathc  
Version: 2019-09-29  
Description: Pure C math library for 2D and 3D programming  
Homepage: https://github.com/felselva/mathc  
control: vcpkg/ports/mathc/CONTROL

Source: mathgl  
Version: 2.4.3-2  
Description: MathGL is a free library of fast C++ routines for the plotting of the data varied in one or more dimensions  
Default-Features: opengl, jpeg, png, zlib  
  
Feature: hdf5  
Build-Depends: hdf5  
Description: hdf5 module  
  
Feature: fltk  
Build-Depends: fltk  
Description: fltk module  
  
Feature: gif  
Build-Depends: giflib  
Description: gif module  
  
Feature: png  
Build-Depends: libpng  
Description: png module  
  
Feature: zlib  
Build-Depends: zlib  
Description: zlib module  
  
Feature: jpeg  
Build-Depends: libjpeg-turbo  
Description: jpeg module  
  
Feature: gsl  
Build-Depends: gsl  
Description: gsl module  
  
Feature: opengl  
Build-Depends: opengl  
Description: opengl module  
  
Feature: glut  
Build-Depends: freeglut  
Description: glut module  
  
Feature: wx  
Build-Depends: wxwidgets  
Description: wx module  
  
Feature: qt5  
Build-Depends: qt5  
Description: qt5 module  
control: vcpkg/ports/mathgl/CONTROL

Source: matio  
Version: 1.5.16  
Homepage: https://github.com/tbeu/matio  
Description: MATLAB MAT File I/O Library  
Build-Depends: zlib, hdf5  
control: vcpkg/ports/matio/CONTROL

Source: matplotlib-cpp  
Version: 2019-09-24  
Description: Extremely simple yet powerful header-only C++ plotting library built on the popular matplotlib  
Homepage: https://github.com/lava/matplotlib-cpp  
control: vcpkg/ports/matplotlib-cpp/CONTROL

Source: matroska  
Version: 1.5.2  
Homepage: https://github.com/Matroska-Org/libmatroska  
Description: a C++ libary to parse Matroska files (.mkv and .mka)  
Build-Depends: ebml  
control: vcpkg/ports/matroska/CONTROL

Source: mbedtls  
Version: 2.16.3  
Homepage: https://github.com/ARMmbed/mbedtls  
Description: An open source, portable, easy to use, readable and flexible SSL library  
control: vcpkg/ports/mbedtls/CONTROL

Source: mdnsresponder  
Version: 765.30.11  
Description: The mDNSResponder project is a component of Bonjour, Apple's ease-of-use IP networking initiative.  
Homepage: https://developer.apple.com/bonjour/  
control: vcpkg/ports/mdnsresponder/CONTROL

Source: mecab  
Version: 1.0  
Description: A morphological analysis engine based on CRF  
control: vcpkg/ports/mecab/CONTROL

Source: meschach  
Version: 1.2b-2  
Homepage: https://homepage.math.uiowa.edu/~dstewart/meschach  
Description: Matrix computations in C  
control: vcpkg/ports/meschach/CONTROL

Source: metis  
Version: 5.1.0-5  
Homepage: https://glaros.dtc.umn.edu/gkhome/metis/metis/overview  
Description: Serial Graph Partitioning and Fill-reducing Matrix Ordering  
control: vcpkg/ports/metis/CONTROL

Source: mgnlibs  
Version: 2019-09-29  
Homepage: https://github.com/mattiasgustavsson/libs  
Description: Single-file public domain libraries for C/C++  
control: vcpkg/ports/mgnlibs/CONTROL

Source: mhook  
Version: 2.5.1-1  
Description: A Windows API hooking library.  
control: vcpkg/ports/mhook/CONTROL

Source: milerius-sfml-imgui  
Version: 1.1-2  
Description: imgui dll for sfml usage  
Build-Depends: sfml (windows), imgui  
control: vcpkg/ports/milerius-sfml-imgui/CONTROL

Source: mimalloc  
Version: 2019-06-25-1  
Description: Compact general purpose allocator with excellent performance  
Homepage: https://github.com/microsoft/mimalloc  
  
Feature: asm  
Description: Generate assembly files  
  
Feature: override  
Description: Override the standard malloc interface  
  
Feature: secure  
Description: Use security mitigations (like guard pages and randomization)  
control: vcpkg/ports/mimalloc/CONTROL

Source: minhook  
Version: 1.3.3  
Description: The Minimalistic x86/x64 API Hooking Library for Windows.  
control: vcpkg/ports/minhook/CONTROL

Source: minifb  
Version: 2019-08-20-1  
Homepage: https://github.com/emoon/minifb  
Description: MiniFB (Mini FrameBuffer) is a small cross platform library that makes it easy to render (32-bit) pixels in a window.  
control: vcpkg/ports/minifb/CONTROL

Source: minimp3  
Version: 2019-07-24-1  
Homepage: https://github.com/lieff/minimp3  
Description: Minimalistic, single-header library for decoding MP3. minimp3 is designed to be small, fast (with SSE and NEON support), and accurate (ISO conformant).  
control: vcpkg/ports/minimp3/CONTROL

Source: minisat-master-keying  
Version: 2.2-mod-2  
Description: A minimalistic high-performance SAT solver  
  This is a modernized, cross-platform, CMake-enabled fork of the original MiniSat.   
Homepage: https://github.com/master-keying/minisat  
control: vcpkg/ports/minisat-master-keying/CONTROL

Source: minitrace  
Version: 2019.02.06  
Description: Simple C/C++ library for producing JSON traces suitable for Chrome's built-in trace viewer.  
control: vcpkg/ports/minitrace/CONTROL

Source: miniupnpc  
Version: 2.1  
Description: UPnP client library/tool to access Internet Gateway Devices  
control: vcpkg/ports/miniupnpc/CONTROL

Source: miniz  
Version: 2.1.0  
Description: Single C source file zlib-replacement library  
control: vcpkg/ports/miniz/CONTROL

Source: minizip  
Version: 1.2.11-5  
Build-Depends: zlib  
Homepage: https://github.com/madler/zlib  
Description: Zip compression library  
  
Feature: bzip2  
Build-Depends: bzip2  
Description: Support compression using bzip2 library  
control: vcpkg/ports/minizip/CONTROL

Source: mio  
Version: 2019-02-10  
Description: Cross-platform header-only C++11 library for memory mapped file IO.  
control: vcpkg/ports/mio/CONTROL

Source: mlpack  
Version: 3.1.1-1  
Description: mlpack is a fast, flexible machine learning library, written in C++, that aims to provide fast, extensible implementations of cutting-edge machine learning algorithms.  
Build-Depends: openblas (!osx), clapack (!osx), boost, armadillo, ensmallen  
  
Feature: tools  
Description: Build command-line executables and tests.  
control: vcpkg/ports/mlpack/CONTROL

Source: mman  
Version: git-f5ff813-2  
Homepage: https://github.com/witwall/mman-win32  
Description: A light implementation of the mmap functions for MinGW.  
control: vcpkg/ports/mman/CONTROL

Source: modp-base64  
Version:  
Description:  
control: vcpkg/ports/modp-base64/CONTROL

Source: mongo-c-driver  
Version: 1.14.0-4  
Build-Depends: libbson, openssl (!windows), zlib  
Description: Client library written in C for MongoDB.  
Homepage: https://github.com/mongodb/mongo-c-driver  
  
Feature: snappy  
Description: Enables snappy compressor support  
Build-Depends: snappy  
control: vcpkg/ports/mongo-c-driver/CONTROL

Source: mongo-cxx-driver  
Version: 3.4.0-3  
Build-Depends: libbson, mongo-c-driver, boost-smart-ptr, boost-optional, boost-utility  
Homepage: https://github.com/mongodb/mongo-cxx-driver  
Description: MongoDB C++ Driver.  
  
Feature: mnmlstc  
Description: Use MNMLSTC/core C++17 polyfill.  
  
Feature: system-mnmlstc  
Description: Use an available version of MNMLSTC on your system as C++17 polyfill.  
  
Feature: boost  
Description: Use Boost C++17 polyfill. The only option under MSVC.  
  
Feature: std-experimental  
Description: Use optional and string_view from std::experimental.  
control: vcpkg/ports/mongo-cxx-driver/CONTROL

Source: mongoose  
Version: 6.15-1  
Description: Embedded web server / embedded networking library  
Homepage: https://cesanta.com/  
control: vcpkg/ports/mongoose/CONTROL

Source: monkeys-audio  
Version: 4.8.3  
Homepage: https://monkeysaudio.com  
Description: Monkey's Audio is an excellent audio compression tool which has multiple advantages over traditional methods.  
  Audio files compressed with it ends with .ape extension.  
control: vcpkg/ports/monkeys-audio/CONTROL

Source: moos-core  
Version: 10.4.0-3  
Description: A very light weight, easy to use middleware.  
Homepage: https://sites.google.com/site/moossoftware/  
control: vcpkg/ports/moos-core/CONTROL

Source: moos-essential  
Version: 10.0.1-1  
Description: a set of useful applications that leverage the core-moos communications layer.  
Homepage: https://sites.google.com/site/moossoftware/  
Build-Depends: moos-core  
control: vcpkg/ports/moos-essential/CONTROL

Source: moos-ui  
Version: 10.0.1-2  
Description: set of user interface tools to use and leverage the MOOS project.  
Homepage: https://sites.google.com/site/moossoftware/  
Build-Depends: moos-core  
control: vcpkg/ports/moos-ui/CONTROL

Source: morton-nd  
Version: 2.0.0  
Description: (C++14) header-only library for fast Morton encoding/decoding in N dimensions.  
control: vcpkg/ports/morton-nd/CONTROL

Source: mosquitto  
Version: 1.6.3  
Build-Depends: c-ares, libwebsockets, openssl, pthreads  
Description: Mosquitto is an open source message broker that implements the MQ Telemetry Transport protocol versions 3.1 and 3.1.1.  
  MQTT provides a lightweight method of carrying out messaging using a publish/subscribe model. This makes it suitable for "machine to machine" messaging such as with low power sensors or mobile devices such as phones, embedded computers or microcontrollers like the Arduino.  
Homepage: https://mosquitto.org/download/  
control: vcpkg/ports/mosquitto/CONTROL

Source: mozjpeg  
Version: 3.2-3  
Homepage: https://github.com/mozilla/mozjpeg  
Description: MozJPEG reduces file sizes of JPEG images while retaining quality and compatibility with the vast majority of the world's deployed decoders. It's compatible with libjpeg API and ABI, and can be used as a drop-in replacement for libjpeg.  
control: vcpkg/ports/mozjpeg/CONTROL

Source: mp3lame  
Version: 3.100  
Homepage: http://lame.sourceforge.net/  
Description: LAME is a high quality MPEG Audio Layer III (MP3) encoder licensed under the LGPL.  
control: vcpkg/ports/mp3lame/CONTROL

Source: mpark-variant  
Version: 1.4.0  
Description: an implementation of C++17 std::variant for C++11/14/17.  
control: vcpkg/ports/mpark-variant/CONTROL

Source: mpfr  
Version: 4.0.2-1  
Homepage: https://www.mpfr.org  
Description: The MPFR library is a C library for multiple-precision floating-point computations with correct rounding  
Build-Depends: mpir  
control: vcpkg/ports/mpfr/CONTROL

Source: mpg123  
Version: 1.25.8-6  
Homepage: https://sourceforge.net/projects/mpg123/  
Description: mpg123 is a real time MPEG 1.0/2.0/2.5 audio player/decoder for layers 1, 2 and 3 (MPEG 1.0 layer 3 also known as MP3).  
control: vcpkg/ports/mpg123/CONTROL

Source: mpi  
Version: 1  
Description: Message Passing Interface (MPI) is a standardized and portable message-passing standard designed by a group of researchers from academia and industry to function on a wide variety of parallel computing architectures. The standard defines the syntax and semantics of a core of library routines useful to a wide range of users writing portable message-passing programs in C, C++, and Fortran. There are several well-tested and efficient implementations of MPI, many of which are open-source or in the public domain.  
Build-Depends: msmpi (windows), openmpi (!windows)  
control: vcpkg/ports/mpi/CONTROL

Source: mpir  
Version: 3.0.0-7  
Homepage: https://github.com/wbhart/mpir  
Description: Multiple Precision Integers and Rationals.  
control: vcpkg/ports/mpir/CONTROL

Source: mpmcqueue  
Version: 2019-07-26  
Description: A bounded multi-producer multi-consumer lock-free queue written in C++11  
Homepage: https://github.com/rigtorp/MPMCQueue  
control: vcpkg/ports/mpmcqueue/CONTROL

Source: ms-angle  
Version: 2018-04-18-2  
Description: The UWP version of a conformant OpenGL ES implementation for Windows, Mac and Linux.  
  The goal of ANGLE is to allow users of multiple operating systems to seamlessly run WebGL and other OpenGL ES content by translating OpenGL ES API calls to one of the hardware-supported APIs available for that platform. ANGLE currently provides translation from OpenGL ES 2.0 and 3.0 to desktop OpenGL, OpenGL ES, Direct3D 9, and Direct3D 11. Support for translation from OpenGL ES to Vulkan is underway, and future plans include compute shader support (ES 3.1) and MacOS support.  
control: vcpkg/ports/ms-angle/CONTROL

Source: ms-gsl  
Version: 2019-07-11  
Homepage: https://github.com/Microsoft/GSL  
Description: Microsoft implementation of the Guidelines Support Library  
control: vcpkg/ports/ms-gsl/CONTROL

Source: msgpack  
Version: 3.2.0  
Homepage: https://github.com/msgpack/msgpack-c  
Description: MessagePack is an efficient binary serialization format, which lets you exchange data among multiple languages like JSON, except that it's faster and smaller.  
control: vcpkg/ports/msgpack/CONTROL

Source: msinttypes  
Version: 2018-02-25  
Homepage: https://github.com/chemeris/msinttypes  
Description: msinttypes is a package to provide missing  ISO C9x  compliant headers for Microsoft Visual Studio  
control: vcpkg/ports/msinttypes/CONTROL

Source: msix  
Version: MsixCoreInstaller-preview-1  
Build-Depends: xerces-c, zlib, openssl (!uwp&!windows)  
Description: The MSIX Packaging SDK project is an effort to enable developers on a variety of platforms to pack and unpack packages for the purposes of distribution from either the Microsoft Store, or their own content distribution networks.  
  The MSIX Packaging APIs that a client app would use to interact with .msix/.appx packages are a subset of those documented here. See sample/ExtractContentsSample/ExtractContentsSample.cpp for additional details.  
control: vcpkg/ports/msix/CONTROL

Source: msmpi  
Version: 10.0-2  
Description: Microsoft MPI  
control: vcpkg/ports/msmpi/CONTROL

Source: mujs  
Version: 2018-07-30-1  
Homepage: https://github.com/ccxvii/mujs  
Description: An embeddable Javascript interpreter in C  
control: vcpkg/ports/mujs/CONTROL

Source: muparser  
Version: 2.2.6.1  
Homepage: https://github.com/beltoforion/muparser  
Description:  Fast math parser library   
control: vcpkg/ports/muparser/CONTROL

Source: nameof  
Version: 2019-07-13  
Description: Nameof operator for modern C++  
Homepage: https://github.com/Neargye/nameof  
control: vcpkg/ports/nameof/CONTROL

Source: nana  
Version: 1.7.1-1  
Homepage: https://github.com/cnjinhao/nana  
Description: Cross-platform library for GUI programming in modern C++ style.  
Build-Depends: libpng, libjpeg-turbo, freetype (!uwp&&!windows), fontconfig (!uwp&&!windows)  
control: vcpkg/ports/nana/CONTROL

Source: nano-signal-slot  
Version: commit-25aa2aa90d450d3c7550c535c7993a9e2ed0764a  
Description: Pure C++17 Signals and Slots  
control: vcpkg/ports/nano-signal-slot/CONTROL

Source: nanodbc  
Version: 2.12.4-4  
Homepage: https://github.com/lexicalunit/nanodbc  
Description: A small C++ wrapper for the native C ODBC API.  
control: vcpkg/ports/nanodbc/CONTROL

Source: nanogui  
Version: 2019-09-23  
Homepage: https://github.com/wjakob/nanogui  
Description: NanoGUI is a minimalistic cross-platform widget library for OpenGL 3.x or higher.  
Build-Depends: glfw3, nanovg, eigen3  
control: vcpkg/ports/nanogui/CONTROL

Source: nanomsg  
Version: 1.1.5-1  
Description: a simple high-performance implementation of several "scalability protocols".  
  These scalability protocols are light-weight messaging protocols which can be used to solve a number of very common messaging patterns, such as request/reply, publish/subscribe, surveyor/respondent, and so forth. These protocols can run over a variety of transports such as TCP, UNIX sockets, and even WebSocket.  
  
Feature: tool  
Description: nanomsg tool (nanocat)  
control: vcpkg/ports/nanomsg/CONTROL

Source: nanopb  
Version: 2019-02-12-2  
Description: A small code-size Protocol Buffers implementation in ANSI C.  
control: vcpkg/ports/nanopb/CONTROL

Source: nanorange  
Version: 0.0.0  
Description: NanoRange is a C++14 implementation of the C++20 Ranges proposals.  
control: vcpkg/ports/nanorange/CONTROL

Source: nanort  
Version: 2019-08-20  
Description: Single header only modern ray tracing kernel  
Homepage: https://github.com/lighttransport/nanort  
control: vcpkg/ports/nanort/CONTROL

Source: nanovg  
Version: 2019-8-30-1  
Homepage: https://github.com/memononen/nanovg  
Description: NanoVG is small antialiased vector graphics rendering library for OpenGL.  
control: vcpkg/ports/nanovg/CONTROL

Source: nativefiledialog  
Version: 2019-08-28  
Description: A tiny, neat C library that portably invokes native file open and save dialogs  
Homepage: https://github.com/mlabbe/nativefiledialog  
  
Feature: zenity  
Description: Using Zenity backend on Linux  
control: vcpkg/ports/nativefiledialog/CONTROL

Source: netcdf-c  
Version: 4.7.0-4  
Build-Depends: hdf5, curl  
Homepage: https://github.com/Unidata/netcdf-c  
Description: a set of self-describing, machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data.  
control: vcpkg/ports/netcdf-c/CONTROL

Source: netcdf-cxx4  
Version: 4.3.0-4  
Build-Depends: netcdf-c  
Homepage: https://github.com/Unidata/netcdf-cxx4  
Description: a set of machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data.  
control: vcpkg/ports/netcdf-cxx4/CONTROL

Source: networkdirect-sdk  
Version: 2.0.1  
Description: The Network Direct architecture allows hardware vendors to expose the advanced capabilities of their networking devices.  
Homepage: https://www.nuget.org/packages/NetworkDirect  
control: vcpkg/ports/networkdirect-sdk/CONTROL

Source: nghttp2  
Version: 1.39.2  
Homepage: https://github.com/nghttp2/nghttp2  
Description: Implementation of the Hypertext Transfer Protocol version 2 in C  
control: vcpkg/ports/nghttp2/CONTROL

Source: nlohmann-json  
Version: 3.7.0  
Homepage: https://github.com/nlohmann/json  
Description: JSON for Modern C++  
control: vcpkg/ports/nlohmann-json/CONTROL

Source: nlopt  
Version: 2.6.1-1  
Homepage: https://github.com/stevengj/nlopt  
Description: a library for nonlinear local and global optimization, for functions with and without gradient information.  
control: vcpkg/ports/nlopt/CONTROL

Source: nmap  
Version: 7.70-1  
Build-Depends: winpcap (windows), libpcap (!windows), lua, openssl, python2 (windows), libssh2, zlib, pcre  
Description: A library for scanning network ports.  
control: vcpkg/ports/nmap/CONTROL

Source: nmslib  
Version: 1.8.1  
Homepage: https://github.com/searchivarius/nmslib  
Description: Non-Metric Space Library (NMSLIB) is an efficient similarity search library and a toolkit for evaluation of k-NN methods for generic non-metric spaces.  
#  
# ## Extras are currently unsupported for Windows, waiting for fixes.  
# Feature: extra  
# Description: Build extra algorithms and tools for nmslib. Note that this feature requires a large bunch of dependencies.  
# Build-Depends: gsl, eigen3, boost-system, boost-filesystem, boost-timer, boost-foreach, boost-format, boost-math, boost-random, boost-dynamic-bitset, boost-program-options  
control: vcpkg/ports/nmslib/CONTROL

Source: nng  
Version: 2019-02-27  
Description: NNG, like its predecessors nanomsg (and to some extent ZeroMQ), is a lightweight, broker-less library, offering a simple API to solve common recurring messaging problems, such as publish/subscribe, RPC-style request/reply, or service discovery.  
  
Feature: mbedtls  
Description: nng built with TLS support(needs mbedTLS)  
Build-Depends: mbedtls  
control: vcpkg/ports/nng/CONTROL

Source: nngpp  
Version: 2019-07-25  
Homepage:https://github.com/cwzx/nngpp  
Description: C++ wrapper around the nanomsg NNG API.  
Build-Depends: nng  
  
control: vcpkg/ports/nngpp/CONTROL

Source: nonius  
Version: 2019-04-20-1  
Description: A C++ micro-benchmarking framework  
Build-Depends: boost-algorithm, boost-lexical-cast, boost-math  
control: vcpkg/ports/nonius/CONTROL

Source: nrf-ble-driver  
Version: 4.1.1-1  
Description: BLE driver is a library for Bluetooth Low Energy communication using Nordic Semiconductor development kits.  
Build-Depends: asio, catch2  
control: vcpkg/ports/nrf-ble-driver/CONTROL

Source: nt-wrapper  
Version: 2019-08-10  
Description: A header only wrapper library around native windows system APIs  
Homepage: https://github.com/JustasMasiulis/nt_wrapper  
control: vcpkg/ports/nt-wrapper/CONTROL

Source: nuklear  
Version: 2019-07-11  
Homepage: https://github.com/vurtun/nuklear  
Description: This is a minimal state immediate mode graphical user interface toolkit written in ANSI C and licensed under public domain  
control: vcpkg/ports/nuklear/CONTROL

Source: numactl  
Version: 2.0.12  
Description: NUMA support for Linux  
control: vcpkg/ports/numactl/CONTROL

Source: nvtt  
Version: 2.1.1  
Description: Texture processing tools with support for Direct3D 10 and 11 formats.  
control: vcpkg/ports/nvtt/CONTROL

Source: observer-ptr-lite  
Version: 0.4.0  
Description: A C++17-like observer_ptr for C++98 and later in a single-file header-only library  
control: vcpkg/ports/observer-ptr-lite/CONTROL

Source: octomap  
Version: 2017-03-11-7  
Description: An Efficient Probabilistic 3D Mapping Framework Based on Octrees  
control: vcpkg/ports/octomap/CONTROL

Source: ode  
Version: 0.15.1-2  
Homepage: https://bitbucket.org/odedevs/ode/src/default/  
Description: Open Dynamics Engine  
control: vcpkg/ports/ode/CONTROL

Source: offscale-libetcd-cpp  
Version: 2019-07-10  
Homepage: https://github.com/offscale/libetcd-cpp  
Description: A C++ client library for etcd. etcd is a distributed, reliable key-value store.  
Build-Depends: grpc, protobuf  
control: vcpkg/ports/offscale-libetcd-cpp/CONTROL

Source: ogdf  
Version: 2019-08-23  
Homepage: https://github.com/ogdf/ogdf  
Description: Open Graph Drawing Framework  
control: vcpkg/ports/ogdf/CONTROL

Source: ogre  
Version: 1.12.1  
Build-Depends: freeimage, freetype, zlib, zziplib  
Homepage: https://github.com/OGRECave/ogre  
Description: 3D Object-Oriented Graphics Rendering Engine  
  
Feature: d3d9  
Description: Build Direct3D9 RenderSystem  
  
Feature: csharp  
Description: Build csharp bindings  
  
Feature: java  
Description: Build Java (JNI) bindings  
  
Feature: python  
Description: Build Python bindings  
Build-Depends: python3  
control: vcpkg/ports/ogre/CONTROL

Source: ompl  
Version: 1.4.2-2  
Description: The Open Motion Planning Library, consists of many state-of-the-art sampling-based motion planning algorithms  
Build-Depends: boost-disjoint-sets, boost-dynamic-bitset, boost-filesystem, boost-graph, boost-odeint, boost-program-options, boost-serialization, boost-system, boost-test, boost-ublas, boost-timer, eigen3  
  
Feature: app  
Description: Add support for reading meshes and performing collision checking  
Build-Depends: assimp, fcl  
control: vcpkg/ports/ompl/CONTROL

Source: oniguruma  
Version: 6.9.3  
Description: Modern and flexible regular expressions library  
Homepage: https://github.com/kkos/oniguruma  
  
Feature: non-posix  
Description: Disable POSIX API  
control: vcpkg/ports/oniguruma/CONTROL

Source: open62541  
Version: 0.3.0-4  
Description: open62541 is an open source C (C99) implementation of OPC UA licensed under the Mozilla Public License v2.0.  
control: vcpkg/ports/open62541/CONTROL

Source: openal-soft  
Version: 1.19.1-2  
Homepage: https://github.com/kcat/openal-soft  
Description: OpenAL Soft is an LGPL-licensed, cross-platform, software implementation of the OpenAL 3D audio API.  
control: vcpkg/ports/openal-soft/CONTROL

Source: openblas  
Version: 0.3.6-6  
Homepage: https://github.com/xianyi/OpenBLAS  
Build-Depends: pthread (linux)  
Description: OpenBLAS is an optimized BLAS library based on GotoBLAS2 1.13 BSD version.  
control: vcpkg/ports/openblas/CONTROL

Source: opencl  
Version: 2.2 (2018.08.31)  
Homepage: https://github.com/KhronosGroup/OpenCL-Headers  
Description: C/C++ headers and ICD loader (Installable Client Driver) for OpenCL  
  
Feature: wdk  
Description: Windows Driver Kit support  
control: vcpkg/ports/opencl/CONTROL

Source: opencolorio  
Version: 1.1.1  
Homepage: https://opencolorio.org/  
Description: OpenColorIO (OCIO) is a complete color management solution geared towards motion picture production with an emphasis on visual effects and computer animation. OCIO provides a straightforward and consistent user experience across all supporting applications while allowing for sophisticated back-end configuration options suitable for high-end production usage. OCIO is compatible with the Academy Color Encoding Specification (ACES) and is LUT-format agnostic, supporting many popular formats.  
Build-Depends: glew[core], freeglut[core], lcms[core], yaml-cpp[core], tinyxml[core]  
  
Feature: applications  
Description: Enable OpenColorIO tools  
Build-Depends: openimageio[core], openexr[core]  
control: vcpkg/ports/opencolorio/CONTROL

Source: opencsg  
Version: 1.4.2-1  
Build-Depends: glew  
Description: OpenCSG is a library that does image-based CSG rendering using OpenGL. OpenCSG is written in C++ and supports most modern graphics hardware using Microsoft Windows or the Linux operating system.  
control: vcpkg/ports/opencsg/CONTROL

Source: opencv  
Version: 4.1.1-1  
Homepage: https://github.com/opencv/opencv  
Description: Computer vision library  
Build-Depends: opencv4[core]  
Default-Features: dnn, jpeg, opengl, png, tiff, webp  
  
Feature: nonfree  
Build-Depends: opencv4[nonfree]  
Description: opencv nonfree module  
  
Feature: ade  
Build-Depends: opencv4[ade]  
Description: graph api  
  
Feature: contrib  
Build-Depends: opencv4[contrib]  
Description: opencv_contrib module  
  
Feature: cuda  
Build-Depends: opencv4[cuda]  
Description: CUDA support for opencv  
  
Feature: dnn  
Build-Depends: opencv4[dnn]  
Description: Enable dnn module  
  
Feature: eigen  
Build-Depends: opencv4[eigen]  
Description: Eigen support for opencv  
  
Feature: ffmpeg  
Build-Depends: opencv4[ffmpeg]  
Description: ffmpeg support for opencv  
  
Feature: gdcm  
Build-Depends: opencv4[gdcm]  
Description: GDCM support for opencv  
  
Feature: ipp  
Build-Depends: opencv4[ipp]  
Description: Enable Intel Integrated Performance Primitives  
  
Feature: jasper  
Build-Depends: opencv4[jasper]  
Description: JPEG 2000 support for opencv  
  
Feature: jpeg  
Build-Depends: opencv4[jpeg]  
Description: JPEG support for opencv  
  
Feature: openexr  
Build-Depends: opencv4[openexr]  
Description: OpenEXR support for opencv  
  
Feature: opengl  
Build-Depends: opencv4[opengl]  
Description: opengl support for opencv  
  
Feature: openmp  
Build-Depends: opencv4[openmp]  
Description: Enable openmp support for opencv  
  
Feature: ovis  
Build-Depends: opencv4[ovis]  
Description: opencv_ovis module  
  
Feature: png  
Build-Depends: opencv4[png]  
Description: PNG support for opencv  
  
Feature: qt  
Build-Depends: opencv4[qt]  
Description: Qt GUI support for opencv  
  
Feature: sfm  
Build-Depends: opencv4[sfm]  
Description: opencv_sfm module  
  
Feature: tbb  
Build-Depends: opencv4[tbb]  
Description: Enable Intel Threading Building Blocks  
  
Feature: tiff  
Build-Depends: opencv4[tiff]  
Description: TIFF support for opencv  
  
Feature: vtk  
Build-Depends: opencv4[vtk]  
Description: vtk support for opencv  
  
Feature: webp  
Build-Depends: opencv4[webp]  
Description: WebP support for opencv  
  
Feature: halide  
Build-Depends: opencv4[halide]  
Description: Halide support for opencv  
  
Feature: world  
Build-Depends: opencv4[world]  
Description: Compile to a single package support for opencv  
control: vcpkg/ports/opencv/CONTROL

Source: opencv3  
Version: 3.4.7-1  
Build-Depends: protobuf, zlib  
Homepage: https://github.com/opencv/opencv  
Description: computer vision library  
Default-Features: dnn, jpeg, opengl, png, tiff, webp  
  
Feature: nonfree  
Description: allow nonfree and unredistributable libraries  
  
Feature: flann  
Description: opencv_flann module  
  
Feature: contrib  
Build-Depends: opencv3[dnn], hdf5 (!uwp)  
Description: opencv_contrib module  
  
Feature: cuda  
Build-Depends: opencv3[contrib], cuda  
Description: CUDA support for opencv  
  
Feature: dnn  
Build-Depends: opencv3[flann]  
Description: Enable dnn module  
  
Feature: eigen  
Build-Depends: eigen3  
Description: Eigen support for opencv  
  
Feature: ffmpeg  
Build-Depends: ffmpeg  
Description: ffmpeg support for opencv  
  
Feature: gdcm  
Build-Depends: gdcm  
Description: GDCM support for opencv  
  
Feature: ipp  
Description: Enable Intel Integrated Performance Primitives  
  
Feature: jasper  
Build-Depends: jasper  
Description: JPEG 2000 support for opencv  
  
Feature: jpeg  
Build-Depends: libjpeg-turbo  
Description: JPEG support for opencv  
  
Feature: openexr  
Build-Depends: openexr  
Description: OpenEXR support for opencv  
  
Feature: opengl  
Build-Depends: opengl  
Description: opengl support for opencv  
  
Feature: ovis  
Build-Depends: opencv3[contrib], ogre  
Description: opencv_ovis module  
  
Feature: png  
Build-Depends: libpng  
Description: PNG support for opencv  
  
Feature: qt  
Build-Depends: qt5  
Description: Qt GUI support for opencv  
  
Feature: sfm  
Build-Depends: opencv3[contrib], eigen3, glog, gflags, ceres  
Description: opencv_sfm module  
  
Feature: tbb  
Build-Depends: tbb  
Description: Enable Intel Threading Building Blocks  
  
Feature: tiff  
Build-Depends: tiff  
Description: TIFF support for opencv  
  
Feature: vtk  
Build-Depends: vtk  
Description: vtk support for opencv  
  
Feature: webp  
Build-Depends: libwebp  
Description: WebP support for opencv  
  
Feature: halide  
Build-Depends: halide, opencv3[core], opencv3[dnn]  
Description: Halide support for opencv  
  
Feature: world  
Description: Compile to a single package support for opencv  
control: vcpkg/ports/opencv3/CONTROL

Source: opencv4  
Version: 4.1.1-2  
Build-Depends: protobuf, zlib  
Homepage: https://github.com/opencv/opencv  
Description: computer vision library  
Default-Features: dnn, jpeg, opengl, png, tiff, webp  
  
Feature: nonfree  
Description: allow nonfree and unredistributable libraries  
  
Feature: ade  
Build-Depends: ade  
Description: graph api  
  
Feature: contrib  
Build-Depends: hdf5 (!uwp)  
Description: opencv_contrib module  
  
Feature: cuda  
Build-Depends: opencv4[contrib], cuda  
Description: CUDA support for opencv  
  
Feature: dnn  
Description: Enable dnn module  
  
Feature: eigen  
Build-Depends: eigen3  
Description: Eigen support for opencv  
  
Feature: ffmpeg  
Build-Depends: ffmpeg  
Description: ffmpeg support for opencv  
  
Feature: gdcm  
Build-Depends: gdcm  
Description: GDCM support for opencv  
  
Feature: ipp  
Description: Enable Intel Integrated Performance Primitives  
  
Feature: jasper  
Build-Depends: jasper  
Description: JPEG 2000 support for opencv  
  
Feature: jpeg  
Build-Depends: libjpeg-turbo  
Description: JPEG support for opencv  
  
Feature: openexr  
Build-Depends: openexr  
Description: OpenEXR support for opencv  
  
Feature: opengl  
Build-Depends: opengl  
Description: opengl support for opencv  
  
Feature: openmp  
Description: Enable openmp support for opencv  
  
Feature: ovis  
Build-Depends: opencv4[contrib], ogre  
Description: opencv_ovis module  
  
Feature: png  
Build-Depends: libpng  
Description: PNG support for opencv  
  
Feature: qt  
Build-Depends: qt5  
Description: Qt GUI support for opencv  
  
Feature: sfm  
Build-Depends: opencv4[contrib], eigen3, glog, gflags, ceres  
Description: opencv_sfm module  
  
Feature: tbb  
Build-Depends: tbb  
Description: Enable Intel Threading Building Blocks  
  
Feature: tiff  
Build-Depends: tiff  
Description: TIFF support for opencv  
  
Feature: vtk  
Build-Depends: vtk  
Description: vtk support for opencv  
  
Feature: webp  
Build-Depends: libwebp  
Description: WebP support for opencv  
  
Feature: halide  
Build-Depends: halide, opencv4[core], opencv4[dnn]  
Description: Halide support for opencv  
  
Feature: world  
Description: Compile to a single package support for opencv  
control: vcpkg/ports/opencv4/CONTROL

Source: openexr  
Version: 2.3.0-4  
Homepage: https://www.openexr.com/  
Description: OpenEXR is a high dynamic-range (HDR) image file format developed by Industrial Light & Magic for use in computer imaging applications  
Build-Depends: zlib  
control: vcpkg/ports/openexr/CONTROL

Source: opengl  
Version: 0.0-5  
Description: Open Graphics Library (OpenGL)[3][4][5] is a cross-language, cross-platform application programming interface (API) for rendering 2D and 3D vector graphics.  
control: vcpkg/ports/opengl/CONTROL

Source: opengl-registry  
Version: 2019-08-22  
Build-Depends: egl-registry  
Description: the API and Extension registries for the OpenGL family APIs  
control: vcpkg/ports/opengl-registry/CONTROL

Source: openigtlink  
Version: 3.0  
Description: OpenIGTLink is an open-source network communication interface specifically designed for image-guided interventions.  
control: vcpkg/ports/openigtlink/CONTROL

Source: openimageio  
Version: 2019-08-08-4  
Homepage: https://github.com/OpenImageIO/oiio  
Description: A library for reading and writing images, and a bunch of related classes, utilities, and application  
Build-Depends: libjpeg-turbo, tiff, libpng, openexr, boost-thread, boost-smart-ptr, boost-foreach, boost-regex, boost-type-traits, boost-static-assert, boost-unordered, boost-config, boost-algorithm, boost-filesystem, boost-system, boost-thread, boost-asio, boost-random, robin-map, boost-stacktrace  
  
Feature: libraw  
Build-Depends: libraw  
Description: Enable RAW image files support  
  
Feature: opencolorio  
Build-Depends: opencolorio  
Description: Enable opencolorio support for openimageio  
control: vcpkg/ports/openimageio/CONTROL

Source: openjpeg  
Version: 2.3.1-1  
Homepage: https://github.com/uclouvain/openjpeg  
Description: JPEG 2000 image library  
control: vcpkg/ports/openjpeg/CONTROL

Source: openmama  
Version: 6.2.3-1  
Build-Depends: libevent, apr, qpid-proton  
Homepage: https://github.com/OpenMAMA/OpenMAMA  
Description: OpenMAMA is a high performance vendor neutral lightweight wrapper that provides a common API interface to different middleware and messaging solutions across a variety of platforms and languages.  
control: vcpkg/ports/openmama/CONTROL

Source: openmesh  
Version: 8.0  
Description: A generic and efficient polygon mesh data structure  
control: vcpkg/ports/openmesh/CONTROL

Source: openmpi  
Version: 4.0.1  
Homepage: https://www.open-mpi.org/  
Description: The Open MPI Project is an open source Message Passing Interface implementation that is developed and maintained by a consortium of academic, research, and industry partners. Open MPI is therefore able to combine the expertise, technologies, and resources from all across the High Performance Computing community in order to build the best MPI library available. Open MPI offers advantages for system and software vendors, application developers and computer science researchers.  
control: vcpkg/ports/openmpi/CONTROL

Source: openmvg  
Version: 1.4-6  
Description: open Multiple View Geometry library. Basis for 3D computer vision and Structure from Motion.  
Build-Depends: coinutils, clp, osi, liblemon, flann, eigen3, ceres, cereal, libjpeg-turbo, tiff, libpng, zlib, suitesparse  
  
Feature: opencv  
Build-Depends: opencv[contrib]  
Description: opencv support for openmvg  
  
Feature: openmp  
Description: openmp support for openmvg  
control: vcpkg/ports/openmvg/CONTROL

Source: openmvs  
Version: 1.0-2  
Description: OpenMVS: open Multi-View Stereo reconstruction library  
Build-Depends: zlib, boost-iostreams, boost-program-options, boost-system, boost-serialization, eigen3, ceres, opencv, cgal[core], glew, glfw3, vcglib  
control: vcpkg/ports/openmvs/CONTROL

Source: openni2  
Version: 2.2.0.33-10  
Build-Depends: kinectsdk1  
Homepage: https://github.com/OpenNI/OpenNI2  
Description: OpenNI is open source library for access to Natural Interaction (NI) devices such as RGB-D camera.  
control: vcpkg/ports/openni2/CONTROL

Source: openssl  
Version: 1  
Homepage: https://www.openssl.org  
Description: OpenSSL is an open source project that provides a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. It is also a general-purpose cryptography library.  
Build-Depends: openssl-windows (windows), openssl-uwp (uwp), openssl-unix (!uwp&!windows)  
control: vcpkg/ports/openssl/CONTROL

Source: openssl-unix  
Version: 1.0.2s-1  
Description: OpenSSL is an open source project that provides a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. It is also a general-purpose cryptography library.  
control: vcpkg/ports/openssl-unix/CONTROL

Source: openssl-uwp  
Version: 1.0.2r  
Description: OpenSSL is an open source project that provides a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. It is also a general-purpose cryptography library.  
control: vcpkg/ports/openssl-uwp/CONTROL

Source: openssl-windows  
Version: 1.0.2s-1  
Description: OpenSSL is an open source project that provides a robust, commercial-grade, and full-featured toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols. It is also a general-purpose cryptography library.  
control: vcpkg/ports/openssl-windows/CONTROL

Source: opentracing  
Version: 1.5.1-1  
Description: C++ implementation of the OpenTracing API  
Homepage: https://opentracing.io  
control: vcpkg/ports/opentracing/CONTROL

Source: openvdb  
Version: 6.1.0  
Build-Depends: boost-ptr-container, openexr, tbb, blosc, boost-iostreams, boost-system, boost-thread, boost-date-time, boost-any, boost-uuid, boost-interprocess, ilmbase  
Homepage: https://github.com/dreamworksanimation/openvdb  
Description: Sparse volume data structure and tools  
  
Feature: tools  
Description: OpenVDB utilities: view, print and render  
Build-Depends: glew, glfw3  
control: vcpkg/ports/openvdb/CONTROL

Source: openvpn3  
Version: 2018-03-21-1  
Build-Depends: asio, tap-windows6 (windows), mbedtls  
Description: a C++ class library that implements the functionality of an OpenVPN client, and is protocol-compatible with the OpenVPN 2.x branch.  
control: vcpkg/ports/openvpn3/CONTROL

Source: openvr  
Version: 1.5.17  
Homepage: https://github.com/ValveSoftware/openvr  
Description: an API and runtime that allows access to VR hardware from multiple vendors without requiring that applications have specific knowledge of the hardware they are targeting.  
control: vcpkg/ports/openvr/CONTROL

Source: openxr-loader  
Version: 2019-09-25  
Description: Khronos API for abstracting VR/MR/AR hardware  
  
Feature: vulkan  
Description: Vulkan functionality for OpenXR  
Build-Depends: vulkan  
control: vcpkg/ports/openxr-loader/CONTROL

Source: optional-bare  
Version: 1.1.0  
Description: A simple version of a C++17-like optional for default-constructible, copyable types, for C++98 and later in a single-file header-only library  
control: vcpkg/ports/optional-bare/CONTROL

Source: optional-lite  
Version: 3.2.0  
Description: A C++17-like optional, a nullable object for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/optional-lite/CONTROL

Source: opus  
Version: 1.3.1  
Homepage: https://github.com/xiph/opus  
Description: Totally open, royalty-free, highly versatile audio codec  
control: vcpkg/ports/opus/CONTROL

Source: opusfile  
Version: 0.11-3  
Homepage: https://github.com/xiph/opusfile  
Description: Stand-alone decoder library for .opus streams  
Build-Depends: libogg, opus  
  
Feature: opusurl  
Description: Support decoding of http(s) streams  
Build-Depends: openssl  
control: vcpkg/ports/opusfile/CONTROL

Source: orc  
Version: 1.5.6  
Homepage: https://orc.apache.org/  
Build-Depends: zlib, protobuf, lz4, snappy, zstd, gtest  
Description: The smallest, fastest columnar storage for Hadoop workloads.  
control: vcpkg/ports/orc/CONTROL

Source: orocos-kdl  
Version: 1.4-2  
Homepage: https://github.com/orocos/orocos_kinematics_dynamics  
Description: Kinematics and Dynamics Library  
Build-Depends: eigen3  
control: vcpkg/ports/orocos-kdl/CONTROL

Source: osg  
Version: 3.6.4  
Homepage: https://github.com/openscenegraph/OpenSceneGraph  
Description:  The OpenSceneGraph is an open source high performance 3D graphics toolkit.  
Build-Depends: freetype, jasper, openexr, zlib, gdal, giflib, libjpeg-turbo, libpng, tiff, fontconfig  
  
Feature: collada  
Description: Support for Collada (.dae) files  
Build-Depends: collada-dom  
control: vcpkg/ports/osg/CONTROL

Source: osg-qt  
Version: Qt4  
Description:  osgQt - Qt project for making use of OpenSceneGraph(OSG)  
Build-Depends: osg, protobuf, qt5-base  
control: vcpkg/ports/osg-qt/CONTROL

Source: osgearth  
Version: 2.10.2  
Description:  osgEarth - Dynamic map generation toolkit for OpenSceneGraph Copyright 2015 Pelican Mapping.  
Build-Depends: osg  
control: vcpkg/ports/osgearth/CONTROL

Source: osi  
Version: 0.108.4-2  
Description: Osi (Open Solver Interface) provides an abstract base class to a generic linear programming (LP) solver, along with derived classes for specific solvers. Many applications may be able to use the Osi to insulate themselves from a specific LP solver.  
Build-Depends: coinutils  
control: vcpkg/ports/osi/CONTROL

Source: otl  
Version: 4.0.443  
Description: Oracle, Odbc and DB2-CLI Template Library  
Homepage: http://otl.sourceforge.net/  
control: vcpkg/ports/otl/CONTROL

Source: outcome  
Version: 2.1  
Homepage: https://github.com/ned14/outcome  
Description: Provides very lightweight outcome<T> and result<T> (non-Boost edition)  
control: vcpkg/ports/outcome/CONTROL

Source: p-ranav-csv  
Version: 2019-07-11  
Description: CSV for modern C++  
Homepage: https://github.com/p-ranav/csv  
control: vcpkg/ports/p-ranav-csv/CONTROL

Source: paho-mqtt  
Version: 1.3.0  
Homepage: https://github.com/eclipse/paho.mqtt.c  
Description: Paho project provides open-source client implementations of MQTT and MQTT-SN messaging protocols aimed at new, existing, and emerging applications for the Internet of Things  
Build-Depends: openssl  
control: vcpkg/ports/paho-mqtt/CONTROL

Source: paho-mqttpp3  
Version: 1.0.1-2  
Description: Paho project provides open-source C++ wrapper for Paho C library  
Build-Depends: paho-mqtt  
Default-Features: ssl  
  
Feature: ssl  
Description: Build with SSL support  
Build-Depends: openssl  
control: vcpkg/ports/paho-mqttpp3/CONTROL

Source: pango  
Version: 1.40.11-4  
Homepage: https://ftp.gnome.org/pub/GNOME/sources/pango/  
Description: Text and font handling library.  
Build-Depends: glib, gettext, cairo, fontconfig, freetype, harfbuzz[glib] (!(windows&static))  
control: vcpkg/ports/pango/CONTROL

Source: pangolin  
Version: 0.5-7  
Build-Depends: eigen3, glew, libpng, libjpeg-turbo, ffmpeg  
Homepage: https://github.com/stevenlovegrove/Pangolin  
Description: Lightweight GUI Library  
control: vcpkg/ports/pangolin/CONTROL

Source: pangomm  
Version: 2.40.1-1  
Homepage: https://ftp.gnome.org/pub/GNOME/sources/pangomm  
Description: pangomm is the official C++ interface for the Pango font layout library. See, for instance, the Pango::Layout class.  
Build-Depends: glib, gettext, cairo, fontconfig, freetype, harfbuzz, pango, cairomm, glibmm  
control: vcpkg/ports/pangomm/CONTROL

Source: parallel-hashmap  
Version: 1.24  
Description: A header-only, very fast and memory-friendly family of C++ hash maps.   
control: vcpkg/ports/parallel-hashmap/CONTROL

Source: parallelstl  
Version: 20190522-1  
Homepage: https://github.com/intel/parallelstl  
Description: Parallel STL is an implementation of the C++ standard library algorithms with support for execution policies, as specified in ISO/IEC 14882:2017 standard, commonly called C++17.  
Build-Depends: tbb  
control: vcpkg/ports/parallelstl/CONTROL

Source: parmetis  
Version: 4.0.3-3  
Homepage: https://glaros.dtc.umn.edu/gkhome/metis/parmetis/overview  
Description: Parallel Graph Partitioning and Fill-reducing Matrix Ordering  
Build-Depends: metis, mpi  
control: vcpkg/ports/parmetis/CONTROL

Source: parquet  
Version: 0  
Build-Depends: arrow  
Description: Parquet-cpp is a C++ library to read and write the Apache Parquet columnar data format.  It is now part of the arrow library.  
control: vcpkg/ports/parquet/CONTROL

Source: parson  
Version: 2019-07-11  
Description: a lighweight json library written in C  
control: vcpkg/ports/parson/CONTROL

Source: pbc  
Version: 0.5.14-1  
Build-Depends: mpir  
Description: Pairing-Based Crypto library provides low-level routines for pairing-based cryptosystems.  
control: vcpkg/ports/pbc/CONTROL

Source: pcg  
Version: 0.98.1  
Description: Permuted Congruential Generator  
control: vcpkg/ports/pcg/CONTROL

Source: pcl  
Version: 1.9.1-9  
Homepage: https://github.com/PointCloudLibrary/pcl  
Description: Point Cloud Library (PCL) is open source library for 2D/3D image and point cloud processing.  
Build-Depends: eigen3, flann, qhull, vtk, libpng, boost-system, boost-filesystem, boost-thread, boost-date-time, boost-iostreams, boost-random, boost-foreach, boost-dynamic-bitset, boost-property-map, boost-graph, boost-multi-array, boost-signals2, boost-ptr-container, boost-uuid, boost-interprocess, boost-asio  
  
Feature: openni2  
Description: OpenNI2 support for PCL  
Build-Depends: openni2  
  
Feature: qt  
Description: Qt support for PCL  
Build-Depends: vtk[qt]  
  
Feature: pcap  
Description: PCAP support for PCL  
Build-Depends: winpcap  
  
Feature: tools  
Description: Build PCL utilities  
Build-Depends: boost-accumulators  
  
Feature: cuda  
Description: CUDA support for PCL  
Build-Depends: cuda  
  
Feature: opengl  
Description: OpenGL support for PCL  
control: vcpkg/ports/pcl/CONTROL

Source: pcre  
Version: 8.41-3  
Homepage: https://www.pcre.org/  
Description: Perl Compatible Regular Expressions  
control: vcpkg/ports/pcre/CONTROL

Source: pcre2  
Version: 10.30-5  
Homepage: https://pcre.org/  
Description: PCRE2 is a re-working of the original Perl Compatible Regular Expressions library  
control: vcpkg/ports/pcre2/CONTROL

Source: pdal  
Version: 1.7.1-5  
Description: PDAL - Point Data Abstraction Library is a library for manipulating point cloud data.  
Build-Depends: gdal, geos, jsoncpp, libgeotiff, laszip  
control: vcpkg/ports/pdal/CONTROL

Source: pdal-c  
Version: 1.8-2  
Description:  C API for the Point Data Abstraction Library (PDAL)  
Build-Depends: pdal  
control: vcpkg/ports/pdal-c/CONTROL

Source: pdcurses  
Version: 3.8  
Homepage: https://sourceforge.net/projects/pdcurses/  
Description: Public Domain Curses - a curses library for environments that don't fit the termcap/terminfo model.  
control: vcpkg/ports/pdcurses/CONTROL

Source: pdqsort  
Version: 2019-07-30  
Homepage: https://github.com/orlp/pdqsort  
Description: Pattern-defeating quicksort (pdqsort) is a novel sorting algorithm  
control: vcpkg/ports/pdqsort/CONTROL

Source: pegtl  
Version: 3.0.0-pre-697aaa0  
Description: The Parsing Expression Grammar Template Library (PEGTL) is a zero-dependency C++ header-only parser combinator library for creating parsers according to a Parsing Expression Grammar (PEG).  
control: vcpkg/ports/pegtl/CONTROL

Source: pegtl-2  
Version: 2.8.1  
Description: The Parsing Expression Grammar Template Library (PEGTL) is a zero-dependency C++ header-only parser combinator library for creating parsers according to a Parsing Expression Grammar (PEG). This version maintains compatibility with C++11.  
control: vcpkg/ports/pegtl-2/CONTROL

Source: pfultz2-linq  
Version: 2019-05-14  
Description: Linq for list comprehension in C++  
Build-Depends: boost-fusion, boost-iterator, boost-mpl, boost-optional, boost-preprocessor, boost-range, boost-static-assert, boost-type-traits, boost-unordered, boost-utility  
control: vcpkg/ports/pfultz2-linq/CONTROL

Source: phnt  
Version: 2019-05-01  
Homepage: https://github.com/processhacker/phnt  
Description: Windows Native API header files  
control: vcpkg/ports/phnt/CONTROL

Source: physfs  
Version: 3.0.2  
Homepage: https://icculus.org/physfs/  
Description: a library to provide abstract access to various archives  
Build-Depends: zlib  
control: vcpkg/ports/physfs/CONTROL

Source: physx  
Version: 4.1.1-1  
Description: The NVIDIA PhysX SDK is a scalable multi-platform physics solution supporting a wide range of devices, from smartphones to high-end multicore CPUs and GPUs  
control: vcpkg/ports/physx/CONTROL

Source: picojson  
Version: 1.3.0  
Homepage: https://github.com/kazuho/picojson  
Description: A header-file-only, JSON parser serializer in C++.  
  
control: vcpkg/ports/picojson/CONTROL

Source: picosha2  
Version: 2018-07-30  
Homepage: https://github.com/okdshin/PicoSHA2  
Description: PicoSHA2 - a C++ SHA256 hash generator  
control: vcpkg/ports/picosha2/CONTROL

Source: piex  
Version: 2019-07-11  
Homepage: https://github.com/google/piex  
Description: The Preview Image Extractor (PIEX) is designed to find and extract the largest  
control: vcpkg/ports/piex/CONTROL

Source: pistache  
Version: 2019-08-05  
Homepage: https://github.com/oktal/pistache  
Description: Pistache is a modern and elegant HTTP and REST framework for C++. It is entirely written in pure-C++11 and provides a clear and pleasant API.  
control: vcpkg/ports/pistache/CONTROL

Source: pixel  
Version: 0.3  
Description: Simple 2D Graphics based on standard and portable OpenGL.  
Build-Depends: glew, opengl, sdl2  
control: vcpkg/ports/pixel/CONTROL

Source: pixman  
Version: 0.38.0-3  
Homepage: https://www.cairographics.org/releases  
Description: Pixman is a low-level software library for pixel manipulation, providing features such as image compositing and trapezoid rasterization.  
control: vcpkg/ports/pixman/CONTROL

Source: platform-folders  
Version: 4.0.0-5  
Description: A C++ library to look for special directories like "My Documents" and "%APPDATA%"  
control: vcpkg/ports/platform-folders/CONTROL

Source: plf-colony  
Version: 2019-08-10  
Description: An unordered data container providing fast iteration/insertion/erasure while maintaining pointer validity to non-erased elements  
Homepage: https://www.plflib.org/  
control: vcpkg/ports/plf-colony/CONTROL

Source: plf-list  
Version: 2019-08-10  
Description: A drop-in replacement for std::list with 293% faster insertion, 57% faster erasure, 17% faster iteration and 77% faster sorting on average  
Homepage: https://www.plflib.org/  
control: vcpkg/ports/plf-list/CONTROL

Source: plf-nanotimer  
Version: 2019-08-10  
Description: A simple C++ 03/11/etc timer class for ~microsecond-precision cross-platform benchmarking  
Homepage: https://www.plflib.org/  
control: vcpkg/ports/plf-nanotimer/CONTROL

Source: plf-stack  
Version: 2019-08-10  
Description: A C++ data container replicating std::stack functionality but with better performance  
Homepage: https://www.plflib.org/  
control: vcpkg/ports/plf-stack/CONTROL

Source: plib  
Version: 1.8.5-3  
Description: A suite of portable game libraries  
control: vcpkg/ports/plib/CONTROL

Source: plibsys  
Version: 0.0.4-2  
Homepage: https://github.com/saprykin/plibsys  
Description: Highly portable C system library: threads and synchronization, sockets, IPC, data structures and more.  
control: vcpkg/ports/plibsys/CONTROL

Source: plog  
Version: 1.1.4  
Homepage: https://github.com/SergiusTheBest/plog  
Description: Portable, simple and extensible C++ logging library.  
control: vcpkg/ports/plog/CONTROL

Source: plplot  
Version: 5.13.0-3  
Build-Depends: freetype, zlib, libpng, bzip2  
Description: PLplot is a cross-platform software package for creating scientific plots whose (UTF-8) plot symbols and text are limited in practice only by what Unicode-aware system fonts are installed on a user's computer.  
  
Feature: wxwidgets  
Build-Depends: wxwidgets  
Description: plplot wxwidgets module  
control: vcpkg/ports/plplot/CONTROL

Source: plustache  
Version: 0.4.0-1  
Description: {{mustaches}} for C++  
Build-Depends: boost-regex, boost-algorithm  
control: vcpkg/ports/plustache/CONTROL

Source: pmdk  
Version: 1.6-1  
Description: Persistent Memory Development Kit  
control: vcpkg/ports/pmdk/CONTROL

Source: pngwriter  
Version: 0.7.0-2  
Build-Depends: zlib, libpng, freetype  
Description: PNGwriter is a very easy to use open source graphics library that uses PNG as its output format  
control: vcpkg/ports/pngwriter/CONTROL

Source: poco  
Version: 1.9.2-1  
Build-Depends: expat, libpq, pcre, sqlite3, zlib, libpng  
Description: Modern, powerful open source C++ class libraries for building network and internet-based applications that run on desktop, server, mobile and embedded systems.  
Homepage: https://github.com/pocoproject/poco  
  
Feature: mysql  
Build-Depends: libmysql  
Description: Mysql support for POCO  
  
Feature: mariadb  
Build-Depends: libmariadb  
Description: MariaDB support for POCO  
  
Feature: postgresql  
Build-Depends: libpqxx  
Description: PostgreSQL support for POCO  
  
Feature: pdf  
Build-Depends: libharu  
Description: Haru support for POCO  
control: vcpkg/ports/poco/CONTROL

Source: podofo  
Version: 0.9.6-7  
Homepage: https://sourceforge.net/projects/podofo/  
Description: PoDoFo is a library to work with the PDF file format  
Build-Depends: zlib, libpng, libjpeg-turbo, tiff, openssl, freetype  
  
Feature: fontconfig  
Description: Enable font manager support on Unix platforms.  
Build-Depends: fontconfig  
control: vcpkg/ports/podofo/CONTROL

Source: polyclipping  
Version: 6.4.2  
Description: The Clipper library performs clipping and offsetting for both lines and polygons. All four boolean clipping operations are supported - intersection, union, difference and exclusive-or. Polygons can be of any shape including self-intersecting polygons.  
control: vcpkg/ports/polyclipping/CONTROL

Source: ponder  
Version: 3.0.0  
Description: A C++ multi-purpose reflection library.  
control: vcpkg/ports/ponder/CONTROL

Source: portable-snippets  
Version: 2019-09-20  
Description: Collection of miscellaneous portable C snippets  
Homepage: https://github.com/nemequ/portable-snippets  
control: vcpkg/ports/portable-snippets/CONTROL

Source: portaudio  
Version: 19.0.6.00-5  
Homepage: https://www.portaudio.com/  
Description: PortAudio Portable Cross-platform Audio I/O API PortAudio is a free, cross-platform, open-source, audio I/O library.  It lets you write simple audio programs in 'C' or C++ that will compile and run on many platforms including Windows, Macintosh OS X, and Unix (OSS/ALSA). It is intended to promote the exchange of audio software between developers on different platforms. Many applications use PortAudio for Audio I/O.  
control: vcpkg/ports/portaudio/CONTROL

Source: portmidi  
Version: 0.217.1  
Homepage: https://sourceforge.net/projects/portmedia/  
Description: Free, cross-platform, open-source I/O library for MIDI  
control: vcpkg/ports/portmidi/CONTROL

Source: ppconsul  
Version: 0.3-1  
Homepage: https://github.com/oliora/ppconsul  
Description: A C++ client library for Consul. Consul is a distributed tool for discovering and configuring services in your infrastructure.  
Build-Depends: boost-core, boost-variant, curl[openssl], json11  
control: vcpkg/ports/ppconsul/CONTROL

Source: pprint  
Version: 2019-07-19  
Description: Pretty Printer for Modern C++  
Homepage: https://github.com/p-ranav/pprint  
control: vcpkg/ports/pprint/CONTROL

Source: pqp  
Version: 1.3-3  
Homepage: https://gamma.cs.unc.edu/SSV/  
Description: a proximity query package  
control: vcpkg/ports/pqp/CONTROL

Source: proj  
Version: 0  
Description: a stub package that pulls in proj4. Do not depend on this package.  
Build-Depends: proj4  
control: vcpkg/ports/proj/CONTROL

Source: proj4  
Version: 4.9.3-4  
Homepage: https://download.osgeo.org/proj  
Description: PROJ.4 library for cartographic projections  
control: vcpkg/ports/proj4/CONTROL

Source: prometheus-cpp  
Version: 0.7.0  
Description: Prometheus Client Library for Modern C++  
Default-Features: compression, pull  
  
Feature: compression  
Build-Depends: zlib  
Description: Enable zlib compression  
  
Feature: tests  
Build-Depends: gtest  
Description: Additional testing support  
  
Feature: pull  
Build-Depends: civetweb  
Description: Support for regular pull mode  
  
Feature: push  
Build-Depends: curl  
Description: Support push gateway  
control: vcpkg/ports/prometheus-cpp/CONTROL

Source: protobuf  
Version: 3.10.0  
Homepage: https://github.com/google/protobuf  
Description: Protocol Buffers - Google's data interchange format  
  
Feature: zlib  
Description: ZLib based features like Gzip streams  
Build-Depends: zlib  
control: vcpkg/ports/protobuf/CONTROL

Source: ptex  
Version: 2.3.2  
Homepage: https://github.com/wdas/ptex  
Description: Per-Face Texture Mapping for Production Rendering.  
Build-Depends: zlib  
control: vcpkg/ports/ptex/CONTROL

Source: pthread  
Version: 3.0.0  
Build-Depends: pthreads  
Description: empty package, linking to other port  
control: vcpkg/ports/pthread/CONTROL

Source: pthreads  
Version: 3.0.0-3  
Homepage: https://sourceware.org/pub/pthreads-win32/  
Description: pthreads for windows  
control: vcpkg/ports/pthreads/CONTROL

Source: pugixml  
Version: 1.10  
Homepage: https://github.com/zeux/pugixml  
Description: C++ XML processing library  
control: vcpkg/ports/pugixml/CONTROL

Source: pybind11  
Version: 2.3.0  
Homepage: https://github.com/pybind/pybind11  
Description: pybind11 is a lightweight header-only library that exposes C++ types in Python and vice versa, mainly to create Python bindings of existing C++ code.  
Build-Depends: python3 (windows)  
control: vcpkg/ports/pybind11/CONTROL

Source: pystring  
Version:  1.1.3-2  
Homepage: https://github.com/imageworks/pystring  
Description: Pystring is a collection of C++ functions which match the interface and behavior of python's string class methods using std::string  
control: vcpkg/ports/pystring/CONTROL

Source: python2  
Version: 2.7.15-1  
Description: The Python programming language as an embeddable library  
control: vcpkg/ports/python2/CONTROL

Source: python3  
Version: 3.7.3  
Homepage: https://github.com/python/cpython  
Description: The Python programming language as an embeddable library  
Build-Depends: libffi, openssl  
control: vcpkg/ports/python3/CONTROL

Source: qca  
Version: 2.2.1  
Description: Qt Cryptographic Architecture (QCA).  
Homepage: https://cgit.kde.org/qca.git/  
Build-Depends: qt5-base  
control: vcpkg/ports/qca/CONTROL

Source: qcustomplot  
Version: 2.0.1-1  
Description: QCustomPlot is a Qt C++ widget for plotting and data visualization.  
Build-Depends: qt5-base  
control: vcpkg/ports/qcustomplot/CONTROL

Source: qhull  
Version: 7.3.2-1  
Homepage: https://github.com/qhull/qhull  
Description: computes the convex hull, Delaunay triangulation, Voronoi diagram  
control: vcpkg/ports/qhull/CONTROL

Source: qpid-proton  
Version: 0.28.0  
Build-Depends: openssl (!windows&!uwp), libuv (osx), jsoncpp  
Homepage: https://github.com/apache/qpid-proton  
Description: Qpid Proton is a high-performance, lightweight messaging library.  
control: vcpkg/ports/qpid-proton/CONTROL

Source: qscintilla  
Version: 2.10-8  
Homepage: https://sourceforge.net/projects/pyqt  
Description: QScintilla is a port to Qt of the Scintilla editing component. Features syntax highlighting, code-completion and much more (Barebone build without python bindings (missing dependeny PyQt) and without QtDesigner plugin)  
Build-Depends: qt5-base, qt5-macextras (osx), qt5-winextras (windows)  
control: vcpkg/ports/qscintilla/CONTROL

Source: qt-advanced-docking-system  
Version: 2019-08-14  
Build-Depends: qt5-base, zlib, bzip2  
Description: Create customizable layouts using an advanced window docking system similar to what is found in many popular IDEs such as Visual Studio  
control: vcpkg/ports/qt-advanced-docking-system/CONTROL

Source: qt5  
Version: 5.12.5  
Homepage: https://www.qt.io/  
Description: Qt5 Application Framework  
Build-Depends: qt5-3d, qt5-activeqt (windows), qt5-base, qt5-charts, qt5-datavis3d, qt5-declarative, qt5-gamepad, qt5-graphicaleffects, qt5-imageformats, qt5-location, qt5-multimedia, qt5-mqtt, qt5-networkauth, qt5-purchasing, qt5-quickcontrols, qt5-quickcontrols2, qt5-script, qt5-scxml, qt5-sensors, qt5-serialport, qt5-speech, qt5-svg, qt5-tools, qt5-virtualkeyboard, qt5-webchannel, qt5-websockets, qt5-winextras (windows), qt5-macextras (osx), qt5-xmlpatterns  
  
Feature: latest  
Build-Depends: qt5-base[latest]  
Description: Build latest qt version (5.13.1) instead of LTS  
control: vcpkg/ports/qt5/CONTROL

Source: qt5-3d  
Version: 5.12.5-1  
Description: Qt5 3d Module - Functionality for near-realtime simulation systems with support for 2D and 3D rendering  
Build-Depends:  qt5-base, qt5-declarative, qt5-imageformats, qt5-gamepad  
control: vcpkg/ports/qt5-3d/CONTROL

Source: qt5-activeqt  
Version: 5.12.5  
Description: Qt5 ActiveQt Module - ActiveX components  
Build-Depends:  qt5-base  
control: vcpkg/ports/qt5-activeqt/CONTROL

Source: qt5-base  
Version: 5.12.5-1  
Homepage: https://www.qt.io/  
Description: Qt5 Application Framework Base Module. Includes Core, GUI, Widgets, Networking, SQL, Concurrent and other essential qt components.  
Build-Depends: zlib, libjpeg-turbo, libpng, freetype, pcre2, harfbuzz, sqlite3, libpq, double-conversion, openssl  
  
Feature: latest  
Description: Build latest qt version (5.13.1) instead of LTS  
control: vcpkg/ports/qt5-base/CONTROL

Source: qt5-charts  
Version: 5.12.5-1  
Description: Qt5 Charts Module - UI components for displaying charts, driven by static or dynamic data models  
Build-Depends:  qt5-base, qt5-declarative, qt5-multimedia  
control: vcpkg/ports/qt5-charts/CONTROL

Source: qt5-connectivity  
Version: 5.12.5-1  
Description: Qt5 Connectivity module - Provides access to Bluetooth and NFC hardware  
Build-Depends:  qt5-base, qt5-androidextras (android)  
control: vcpkg/ports/qt5-connectivity/CONTROL

Source: qt5-datavis3d  
Version: 5.12.5-1  
Description: Qt5 Data Visualization 3d Module - UI Components for creating 3D data visualizations  
Build-Depends:  qt5-base, qt5-declarative, qt5-multimedia  
control: vcpkg/ports/qt5-datavis3d/CONTROL

Source: qt5-declarative  
Version: 5.12.5-1  
Description: Qt5 Declarative (Quick 2) Module. Includes QtQuick, QtQuickParticles, QtQuickWidgets, QtQml, and QtPacketProtocol.  
Build-Depends:  qt5-base, qt5-imageformats, qt5-svg  
control: vcpkg/ports/qt5-declarative/CONTROL

Source: qt5-gamepad  
Version: 5.12.5-1  
Description: Qt5 Gamepad Module - Enables Qt applications to support the use of gamepad hardware  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-gamepad/CONTROL

Source: qt5-graphicaleffects  
Version: 5.12.5  
Description: Qt5 GraphicalEffects Module.  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-graphicaleffects/CONTROL

Source: qt5-imageformats  
Version: 5.12.5-1  
Description: Qt5 Image Formats Module - Plugins for additional image formats: TIFF, MNG, TGA, WBMP  
Build-Depends:  qt5-base, tiff, libwebp  
control: vcpkg/ports/qt5-imageformats/CONTROL

Source: qt5-location  
Version: 5.12.5-1  
Description: Qt5 Location Module - Displays map, navigation, and place content in a QML application.  
Build-Depends:  qt5-base, qt5-declarative, qt5-quickcontrols, qt5-quickcontrols2, qt5-serialport  
control: vcpkg/ports/qt5-location/CONTROL

Source: qt5-macextras  
Version: 5.12.5  
Description: Qt5 Mac Extras Module. Provides platform-specific APIs for mac.  
Build-Depends:  qt5-base  
control: vcpkg/ports/qt5-macextras/CONTROL

Source: qt5-modularscripts  
Version: deprecated  
Description: now part of qt5-base, formerly vcpkg helpers to package qt5 modules  
control: vcpkg/ports/qt5-modularscripts/CONTROL

Source: qt5-mqtt  
Version: 5.12.5  
Description: Qt5 MQTT module.  
Build-Depends:  qt5-base  
control: vcpkg/ports/qt5-mqtt/CONTROL

Source: qt5-multimedia  
Version: 5.12.5-1  
Description: Qt5 Multimedia Module - Classes and widgets for audio, video, radio and camera functionality  
Build-Depends: qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-multimedia/CONTROL

Source: qt5-networkauth  
Version: 5.12.5  
Description: Qt5 Network Authorization Module  
Build-Depends:  qt5-base  
control: vcpkg/ports/qt5-networkauth/CONTROL

Source: qt5-purchasing  
Version: 5.12.5-1  
Description: Qt5 Purchasing Module - Enables in-app purchase of products in Qt applications.  
Build-Depends:  qt5-base, qt5-declarative, qt5-androidextras (android)  
control: vcpkg/ports/qt5-purchasing/CONTROL

Source: qt5-quickcontrols  
Version: 5.12.5-1  
Description: Qt5 QuickControls Module.  
Build-Depends:  qt5-base, qt5-declarative, qt5-graphicaleffects  
control: vcpkg/ports/qt5-quickcontrols/CONTROL

Source: qt5-quickcontrols2  
Version: 5.12.5-1  
Description: Qt5 QuickControls2 Module.  
Build-Depends:  qt5-base, qt5-declarative, qt5-imageformats  
control: vcpkg/ports/qt5-quickcontrols2/CONTROL

Source: qt5-remoteobjects  
Version: 5.12.5-1  
Description: Qt5 Remoteobjects module - Provides an easy to use mechanism for sharing a QObject's API (Properties/Signals/Slots) between processes or devices.  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-remoteobjects/CONTROL

Source: qt5-script  
Version: 5.12.5-1  
Build-Depends: qt5-base, qt5-tools  
Description:Qt5 Script Module.  
control: vcpkg/ports/qt5-script/CONTROL

Source: qt5-scxml  
Version: 5.12.5  
Description: Qt5 SCXML Module - Provides classes and tools for creating state machines from SCXML files and embedding them in applications  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-scxml/CONTROL

Source: qt5-sensors  
Version: 5.12.5-1  
Description: Qt5 Sensors module - Provides access to sensor hardware and motion gesture recognition.  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-sensors/CONTROL

Source: qt5-serialport  
Version: 5.12.5  
Description: Qt5 Serial Port - provides access to hardware and virtual serial ports  
Build-Depends:  qt5-base  
control: vcpkg/ports/qt5-serialport/CONTROL

Source: qt5-speech  
Version: 5.12.5-1  
Description: Qt5 Speech Module  
Build-Depends:  qt5-base, atlmfc (windows), qt5-declarative, qt5-multimedia  
control: vcpkg/ports/qt5-speech/CONTROL

Source: qt5-svg  
Version: 5.12.5  
Description: Qt5 SVG Module - provides classes for displaying the contents of SVG files  
Build-Depends:  qt5-base  
control: vcpkg/ports/qt5-svg/CONTROL

Source: qt5-tools  
Version: 5.12.5-1  
Description: Qt5 Tools Module; Includes deployment tools and helpers, Qt Designer, Assistant, and other applications  
Build-Depends:  qt5-base, qt5-declarative, qt5-activeqt  
control: vcpkg/ports/qt5-tools/CONTROL

Source: qt5-virtualkeyboard  
Version: 5.12.5-1  
Description: Qt5 Virtual Keyboard Module - A framework for implementing different input methods. Supports localized keyboard layouts and custom visual themes  
Build-Depends:  qt5-svg, qt5-quickcontrols, qt5-multimedia, qt5-quickcontrols  
control: vcpkg/ports/qt5-virtualkeyboard/CONTROL

Source: qt5-webchannel  
Version: 5.12.5-1  
Description: Qt5 Web Channel module - Provides access to QObject or QML objects from HTML clients for seamless integration of Qt applications with HTML/JavaScript clients.  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-webchannel/CONTROL

Source: qt5-websockets  
Version: 5.12.5  
Description: Qt5 Web Sockets Module - provides WebSocket communication compliant with RFC 6455  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-websockets/CONTROL

Source: qt5-webview  
Version: 5.12.5-1  
Description: Qt5 WebView module - Provides a way to display web content in a QML application without necessarily including a full web browser stack by using native APIs where it makes sense.  
Build-Depends:  qt5-declarative  
control: vcpkg/ports/qt5-webview/CONTROL

Source: qt5-winextras  
Version: 5.12.5-1  
Description: Qt5 Windows Extras Module. Provides platform-specific APIs for Windows.  
Build-Depends:  qt5-base, atlmfc (windows), qt5-declarative, qt5-multimedia  
control: vcpkg/ports/qt5-winextras/CONTROL

Source: qt5-xmlpatterns  
Version: 5.12.5  
Description: Qt5 XML Patterns Module - Support for XPath, XQuery, XSLT and XML schema validation  
Build-Depends:  qt5-base, qt5-declarative  
control: vcpkg/ports/qt5-xmlpatterns/CONTROL

Source: qtkeychain  
Version: v0.9.1  
Description:  qtkeychain - Platform-independent Qt API for storing passwords securely  
Build-Depends: qt5-base, qt5-tools  
control: vcpkg/ports/qtkeychain/CONTROL

Source: quantlib  
Version: 2019-09-02  
Description: The QuantLib C++ library  
Homepage: https://www.quantlib.org/  
Build-Depends: boost-accumulators, boost-algorithm, boost-any, boost-array, boost-assert, boost-assign, boost-atomic, boost-bind, boost-config, boost-core, boost-date-time, boost-dynamic-bitset, boost-format, boost-function, boost-functional, boost-iterator, boost-lexical-cast, boost-math, boost-multi-array, boost-multiprecision, boost-optional, boost-preprocessor, boost-random, boost-serialization, boost-signals2, boost-smart-ptr, boost-thread, boost-tuple, boost-type-traits, boost-ublas, boost-unordered, boost-utility  
control: vcpkg/ports/quantlib/CONTROL

Source: quickfast  
Version: 1.5  
Build-Depends: boost-asio, xerces-c  
Homepage: https://github.com/objectcomputing/quickfast  
Description: QuickFAST is an Open Source native C++ implementation of the FAST Protocol [SM].  
control: vcpkg/ports/quickfast/CONTROL

Source: quickfix  
Version: 1.15.1  
Build-Depends: openssl  
Homepage: https://github.com/quickfix/quickfix  
Description: QuickFIX is a free and open source implementation of the FIX protocol.  
control: vcpkg/ports/quickfix/CONTROL

Source: quirc  
Version: 1.0-3  
Description: quirc is one of the C library available for scanning QR Codes  
control: vcpkg/ports/quirc/CONTROL

Source: qwt  
Version: 6.1.3-8  
Homepage: https://sourceforge.net/projects/qwt  
Description: Qt widgets library for technical applications  
Build-Depends: qt5-base, qt5-svg, qt5-tools  
control: vcpkg/ports/qwt/CONTROL

Source: rabit  
Version: 0.1-2  
Homepage: https://github.com/dmlc/rabit  
Description: rabit is a light weight library that provides a fault tolerant interface of Allreduce and Broadcast. It is designed to support easy implementations of distributed machine learning programs, many of which fall naturally under the Allreduce abstraction.  
Build-Depends: dmlc  
  
control: vcpkg/ports/rabit/CONTROL

Source: ragel  
Version: 6.10-2  
Homepage: https://www.colm.net/files/ragel  
Description: Ragel State Machine Compiler  
control: vcpkg/ports/ragel/CONTROL

Source: rang  
Version: 3.1.0  
Description: Colors for your Terminal.  
control: vcpkg/ports/rang/CONTROL

Source: range-v3  
Version: 0.9.0-20190822  
Homepage: https://github.com/ericniebler/range-v3  
Description: Range library for C++11/14/17.  
control: vcpkg/ports/range-v3/CONTROL

Source: range-v3-vs2015  
Version: 20151130-vcpkg5  
Homepage: https://github.com/Microsoft/Range-V3-VS2015  
Description: Range library for C++11/14/17.  
control: vcpkg/ports/range-v3-vs2015/CONTROL

Source: rapidcheck  
Version: 2018-11-05-1  
Description: A property-based testing library for C++ (a la QuickCheck) with the goal of being simple to use with as little boilerplate as possible.  
control: vcpkg/ports/rapidcheck/CONTROL

Source: rapidjson  
Version: d87b698-1  
Description: A fast JSON parser/generator for C++ with both SAX/DOM style API <http://rapidjson.org/>  
Homepage: http://rapidjson.org/  
control: vcpkg/ports/rapidjson/CONTROL

Source: rapidstring  
Version: 2018-08-03  
Description: rapidstring is maybe the fastest string library ever written in ANSI C.  
control: vcpkg/ports/rapidstring/CONTROL

Source: rapidxml  
Version: 1.13  
Homepage: https://sourceforge.net/projects/rapidxml  
Description: RapidXml is an attempt to create the fastest XML parser possible, while retaining useability, portability and reasonable W3C compatibility.  
control: vcpkg/ports/rapidxml/CONTROL

Source: rapidxml-ns  
Version: 1.13.2  
Description: RapidXML with added XML namespaces support.  
control: vcpkg/ports/rapidxml-ns/CONTROL

Source: raylib  
Version: 2.5.0  
Description: A simple and easy-to-use library to enjoy videogames programming  
#Build-Depends: glfw3  
  
Feature: non-audio  
Description: Build raylib without audio module  
control: vcpkg/ports/raylib/CONTROL

Source: re2  
Version: 2019-09-01  
Homepage: https://github.com/google/re2  
Description: RE2 is a fast, safe, thread-friendly alternative to backtracking regular expression engines like those used in PCRE, Perl, and Python. It is a C++ library.  
control: vcpkg/ports/re2/CONTROL

Source: readerwriterqueue  
Version: 1.0.0-1  
Description: A single-producer, single-consumer lock-free queue  
control: vcpkg/ports/readerwriterqueue/CONTROL

Source: readline  
Version: 0  
Description: GNU readline and history libraries  
Build-Depends: readline-win32 (windows)  
control: vcpkg/ports/readline/CONTROL

Source: readline-win32  
Version: 5.0-2  
Description: Implementation of readline for Windows Desktop  
Homepage: https://github.com/lltcggie  
control: vcpkg/ports/readline-win32/CONTROL

Source: readosm  
Version: 1.1.0-1  
Homepage: https://www.gaia-gis.it/gaia-sins/readosm-sources  
Description: ReadOSM is an open source library to extract valid data from within an Open Street Map input file (.osm or .osm.pbf)  
Build-Depends: expat, zlib  
control: vcpkg/ports/readosm/CONTROL

Source: realsense2  
Version: 2.22.0-2  
Homepage: https://github.com/IntelRealSense/librealsense  
Description: Intel® RealSense™ SDK 2.0 is a cross-platform library for Intel® RealSense™ depth cameras (D400 series and the SR300).  
  
Feature: tools  
Build-Depends: opengl, glfw3  
Description: Build Intel® RealSense™ examples and tools  
  
Feature: openni2  
Build-Depends: openni2  
Description: Build Intel® RealSense™ OpenNI2 driver  
control: vcpkg/ports/realsense2/CONTROL

Source: recast  
Version: 1.5.1-3  
Homepage: https://github.com/recastnavigation/recastnavigation  
Description: Navigation-mesh Toolset for Games  
control: vcpkg/ports/recast/CONTROL

Source: refprop-headers  
Version: 2017-11-7-882aec454b2bc3d5323b8691736ff09c288f4ed6  
Homepage: https://github.com/CoolProp/REFPROP-headers  
Description: The REFPROP Headers  
control: vcpkg/ports/refprop-headers/CONTROL

Source: reproc  
Version: 9.0.0  
Description: Cross-platform (C99/C++11) process library  
control: vcpkg/ports/reproc/CONTROL

Source: restbed  
Version: 4.16-07-28-2018-1  
Description: Corvusoft's Restbed framework brings asynchronous RESTful functionality to C++11 applications.  
Build-Depends: asio  
  
Feature: openssl  
Build-Depends: openssl  
Description: Secure over the wire communication allowing you to transmit private data online.  
control: vcpkg/ports/restbed/CONTROL

Source: restclient-cpp  
Version: 0.5.1-2  
Build-Depends: curl  
Description: Binn is a binary data serialization format designed to be compact, fast and easy to use.  
control: vcpkg/ports/restclient-cpp/CONTROL

Source: restinio  
Version: 0.6.0  
Description: A header-only C++14 library that gives you an embedded HTTP/Websocket server targeted primarily for asynchronous processing of HTTP-requests.  
Build-Depends: asio, fmt, http-parser  
control: vcpkg/ports/restinio/CONTROL

Source: rhash  
Version: 1.3.8  
Homepage: https://github.com/rhash/RHash  
Description: C library for computing a wide variety of hash sums  
control: vcpkg/ports/rhash/CONTROL

Source: riffcpp  
Version: 2.2.4  
Homepage: https://github.com/libdmusic/riffcpp  
Description: Simple library for reading RIFF files  
control: vcpkg/ports/riffcpp/CONTROL

Source: ring-span-lite  
Version: 0.3.0  
Description: A C++yy-like ring_span type for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/ring-span-lite/CONTROL

Source: roaring  
Version: 2019-03-05-2  
Description: A better compressed bitset in C (and C++)  
control: vcpkg/ports/roaring/CONTROL

Source: robin-hood-hashing  
Version: 3.4.0  
Description: Fast & memory efficient hashtable based on robin hood hashing for C++14  
control: vcpkg/ports/robin-hood-hashing/CONTROL

Source: robin-map  
Version: 0.6.1  
Description: A C++ implementation of a fast hash map and hash set using robin hood hashing  
control: vcpkg/ports/robin-map/CONTROL

Source: rocksdb  
Version: 6.1.2-1  
Homepage: https://github.com/facebook/rocksdb  
Description: A library that provides an embeddable, persistent key-value store for fast storage  
Default-Features: zlib  
  
Feature: lz4  
Build-Depends: lz4  
Description: lz4 support in rocksdb  
  
Feature: snappy  
Build-Depends: snappy  
Description: snappy support in rocksdb  
  
Feature: zlib  
Build-Depends: zlib  
Description: zlib support in rocksdb  
  
Feature: tbb  
Build-Depends: tbb  
Description: tbb support in rocksdb  
  
Feature: zstd  
Build-Depends: zstd  
Description: zstd support in rocksdb  
control: vcpkg/ports/rocksdb/CONTROL

Source: rpclib  
Version: 2.2.1-1  
Homepage: https://github.com/rpclib/rpclib  
Description: a RPC library for C++, providing both a client and server implementation. It is built using modern C++14.  
control: vcpkg/ports/rpclib/CONTROL

Source: rs-core-lib  
Version: 2019-07-11  
Homepage: https://github.com/CaptainCrowbar/rs-core-lib  
Description: Minimal common utilities by Ross Smith  
  
control: vcpkg/ports/rs-core-lib/CONTROL

Source: rtmidi  
Version: 4.0.0  
Homepage: https://github.com/thestk/rtmidi  
Description: A set of C++ classes that provide a common API for realtime MIDI input/output across Linux (ALSA & JACK), Macintosh OS X (CoreMidi & JACK) and Windows (Multimedia)  
control: vcpkg/ports/rtmidi/CONTROL

Source: rttr  
Version: 0.9.6-1  
Homepage: https://github.com/rttrorg/rttr  
Description: an easy and intuitive way to use reflection in C++  
control: vcpkg/ports/rttr/CONTROL

Source: rxcpp  
Version: 4.1.0  
Homepage: https://github.com/ReactiveX/RxCpp  
Description: Reactive Extensions for C++  
control: vcpkg/ports/rxcpp/CONTROL

Source: rxqt  
Version: bb2138c  
Description: The Reactive Extensions for Qt.  
Homepage: https://github.com/tetsurom/rxqt  
Build-Depends: rxcpp  
control: vcpkg/ports/rxqt/CONTROL

Source: safeint  
Version: 3.21  
Description: SafeInt is a class library for C++ that manages integer overflows  
control: vcpkg/ports/safeint/CONTROL

Source: sais  
Version: 2.4.1  
Description: An implementation of the induced sorting algorithm  
control: vcpkg/ports/sais/CONTROL

Source: sajson  
Version: 2018-09-21  
Description: Lightweight, extremely high-performance JSON parser for C++11  
control: vcpkg/ports/sajson/CONTROL

Source: scintilla  
Version: 4.1.2  
Homepage: https://www.scintilla.org/  
Description: A free source code editing component for Win32, GTK+, and OS X  
control: vcpkg/ports/scintilla/CONTROL

Source: sciter  
Version: 4.2.6.9-1  
Homepage: https://github.com/c-smile/sciter-sdk  
Description: Sciter is an embeddable HTML/CSS/scripting engine.  
Maintainer: andrew.fedoniouk@gmail.com, ehysta@gmail.com  
control: vcpkg/ports/sciter/CONTROL

Source: scnlib  
Version:  0.1.2  
Description: scnlib is a modern C++ library for replacing scanf and std::istream  
Homepage: https://scnlib.dev/  
control: vcpkg/ports/scnlib/CONTROL

Source: scylla-wrapper  
Version: 2018-08-26-16e6f435  
Build-Depends: distorm  
Description: This is a wrapper around Scylla.  It exports functions for IAT fixing, dumping and PE rebuilding. based on https://github.com/NtQuery/Scylla commit 0f6b7198be  (v0.9.6b).  
control: vcpkg/ports/scylla-wrapper/CONTROL

Source: sdformat6  
Version: 6.2.0  
Homepage: http://sdformat.org/  
Build-Depends: boost-any, boost-variant, ignition-math4, urdfdom, tinyxml  
Description: Simulation Description Format (SDF) parser and description files.  
control: vcpkg/ports/sdformat6/CONTROL

Source: sdl1  
Version: 1.2.15-8  
Description: Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.  
control: vcpkg/ports/sdl1/CONTROL

Source: sdl1-net  
Version: 1.2.8-3  
Description: Networking library for SDL  
Build-Depends: sdl1  
control: vcpkg/ports/sdl1-net/CONTROL

Source: sdl2  
Version: 2.0.9-4  
Homepage: https://github.com/SDL-Mirror/SDL  
Description: Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.  
  
Feature: vulkan  
Description: Vulkan functionality for SDL  
Build-Depends: vulkan  
control: vcpkg/ports/sdl2/CONTROL

Source: sdl2-gfx  
Version: 1.0.4-2  
Build-Depends: sdl2  
Description: Graphics primitives (line, circle, rectangle etc.) with AA support, rotozoomer and other drawing related support functions wrapped up in a C based add-on library for the Simple Direct Media (SDL) cross-platform API layer.  
control: vcpkg/ports/sdl2-gfx/CONTROL

Source: sdl2-image  
Version: 2.0.5  
Build-Depends: sdl2, libpng  
Homepage: https://www.libsdl.org/projects/SDL_image  
Description: SDL_image is an image file loading library. It loads images as SDL surfaces and textures, and supports the following formats: BMP, GIF, JPEG, LBM, PCX, PNG, PNM, TGA, TIFF, WEBP, XCF, XPM, XV  
  
Feature: libjpeg-turbo  
Description: Support for JPEG image format  
Build-Depends: libjpeg-turbo  
  
Feature: tiff  
Description: Support for TIFF image format  
Build-Depends: tiff  
  
Feature: libwebp  
Description: Support for WEBP image format.  
Build-Depends: libwebp  
control: vcpkg/ports/sdl2-image/CONTROL

Source: sdl2-mixer  
Version: 2.0.4-6  
Homepage: https://www.libsdl.org/projects/SDL_mixer  
Description: Multi-channel audio mixer library for SDL.  
Build-Depends: sdl2  
  
Feature: libflac  
Description: Support for FLAC audio format.  
Build-Depends: libflac  
  
Feature: mpg123  
Description: Support for MP3 audio format.  
Build-Depends: mpg123  
  
Feature: libmodplug  
Description: Support for MOD audio format.  
Build-Depends: libmodplug  
  
Feature: libvorbis  
Description: Support for OGG Vorbis audio format.  
Build-Depends: libvorbis  
  
Feature: opusfile  
Description: Support for Opus audio format.  
Build-Depends: opusfile  
control: vcpkg/ports/sdl2-mixer/CONTROL

Source: sdl2-net  
Version: 2.0.1-7  
Homepage: https://www.libsdl.org/projects/SDL_net  
Description: Networking library for SDL  
Build-Depends: sdl2  
control: vcpkg/ports/sdl2-net/CONTROL

Source: sdl2-ttf  
Version: 2.0.15-3  
Homepage: https://www.libsdl.org/projects/SDL_ttf/  
Description: A library for rendering TrueType fonts with SDL  
Build-Depends: sdl2, freetype  
control: vcpkg/ports/sdl2-ttf/CONTROL

Source: sdl2pp  
Version: 0.16.0-1  
Description: C++11 bindings/wrapper for SDL2  
Homepage: https://sdl2pp.amdmi3.ru  
Build-Depends: sdl2, sdl2-mixer, sdl2-image, sdl2-ttf  
control: vcpkg/ports/sdl2pp/CONTROL

Source: secp256k1  
Version: 2017-19-10-0b7024185045a49a1a6a4c5615bf31c94f63d9c4-2  
Homepage: https://github.com/bitcoin-core/secp256k1  
Description: Optimized C library for EC operations on curve  
control: vcpkg/ports/secp256k1/CONTROL

Source: selene  
Version: 0.3.1-1  
Homepage: https://github.com/kmhofmann/selene  
Description: A C++17 image representation, processing and I/O library.  
Build-Depends: zlib, libpng, libjpeg-turbo, tiff  
control: vcpkg/ports/selene/CONTROL

Source: sentencepiece  
Version: v0.1.82  
Description: SentencePiece is an unsupervised text tokenizer and detokenizer mainly for Neural Network-based text generation systems where the vocabulary size is predetermined prior to the neural model training  
control: vcpkg/ports/sentencepiece/CONTROL

Source: septag-sx  
Version: 2019-05-07-2  
Description: Portable base library for C programmers, designed for performance and simplicity.  
control: vcpkg/ports/septag-sx/CONTROL

Source: seqan  
Version: 2.4.0  
Description: SeqAn is an open source C++ library of efficient algorithms and data structures for the analysis of sequences with the focus on biological data.  
control: vcpkg/ports/seqan/CONTROL

Source: sf2cute  
Version: 0.2.0-1  
Description: C++14 Library for SoundFont 2  
  
Feature: example  
Description: Installs an example application  
control: vcpkg/ports/sf2cute/CONTROL

Source: sfgui  
Version: 0.4.0  
Homepage: https://github.com/TankOs/SFGUI  
Description: simple and fast graphical user interface library  
Build-Depends: sfml  
control: vcpkg/ports/sfgui/CONTROL

Source: sfml  
Version: 2.5.1-2  
Homepage: https://github.com/sfml/sfml  
Description: Simple and fast multimedia library  
Build-Depends: freetype, libflac, libogg, libvorbis, openal-soft, stb  
control: vcpkg/ports/sfml/CONTROL

Source: shaderc  
Version: 2019-06-26-1  
Homepage: https://github.com/google/shaderc  
Description: A collection of tools, libraries and tests for shader compilation.  
Build-Depends: glslang, spirv-tools  
control: vcpkg/ports/shaderc/CONTROL

Source: shapelib  
Version: 1.4.1-1  
Homepage: https://download.osgeo.org/shapelib  
Description: Shapefile C Library is simple C API for reading and writing ESRI Shapefiles  
control: vcpkg/ports/shapelib/CONTROL

Source: shiva  
Version: 1.0-2  
Description: Modern C++ Game Engine  
Build-Depends: boost-stacktrace, boost-filesystem, boost-dll, entt, lua, luafilesystem (windows), sol2, pybind11, spdlog, nlohmann-json  
control: vcpkg/ports/shiva/CONTROL

Source: shiva-sfml  
Version: 1.0  
Description: shiva-sfml plugins of shiva C++ engine  
Build-Depends: sfml (windows), shiva  
control: vcpkg/ports/shiva-sfml/CONTROL

Source: shogun  
Version: 6.1.4  
Build-Depends: bzip2, eigen3, liblzma, libxml2, openblas (x64&!osx), nlopt, rxcpp, snappy, zlib, protobuf, curl, lzo, dirent  
Description: Unified and efficient Machine Learning  
control: vcpkg/ports/shogun/CONTROL

Source: signalrclient  
Version: 1.0.0-beta1-7  
Build-Depends: cpprestsdk, openssl  
Homepage: https://github.com/aspnet/SignalR-Client-Cpp  
Description: C++ client for SignalR.  
control: vcpkg/ports/signalrclient/CONTROL

Source: sigslot  
Version: 1.0.0  
Description: Portable C++ type-safe, thread-safe signal/slot library for ISO C++, Unix/BSD/Linux and Win32. Sigslot allows C++ code to use the signal/slot paradigm made popular by, for example, Qt.  
control: vcpkg/ports/sigslot/CONTROL

Source: simde  
Version: 2019-06-05  
Description: Implementations of SIMD instruction sets for systems which don't natively support them  
control: vcpkg/ports/simde/CONTROL

Source: simdjson  
Version: 2019-08-05  
Description: A extremely fast JSON library that can parse gigabytes of JSON per second  
Homepage: https://github.com/lemire/simdjson  
control: vcpkg/ports/simdjson/CONTROL

Source: simpleini  
Version: 2018-08-31-2  
Description: Cross-platform C++ library providing a simple API to read and write INI-style configuration files  
control: vcpkg/ports/simpleini/CONTROL

Source: smpeg2  
Version: 2.0.0-6  
Homepage: https://www.libsdl.org/projects/smpeg/  
Description: SDL MPEG Player Library  
Build-Depends: sdl2  
control: vcpkg/ports/smpeg2/CONTROL

Source: snappy  
Version: 1.1.7-2  
Homepage: https://github.com/google/snappy  
Description: A fast compressor/decompressor.  
control: vcpkg/ports/snappy/CONTROL

Source: sndfile  
Version: 0  
Description:x Library to read, write and manipulate many soundfile types.  
Build-Depends: libsndfile  
Default-Features: external-libs  
  
Feature: external-libs  
Description: Support Ogg Vorbis and FLAC audio files  
Build-Depends: libsndfile[external-libs]  
control: vcpkg/ports/sndfile/CONTROL

Source: snowhouse  
Version: 3.1.1  
Description: An assertion library for C++  
control: vcpkg/ports/snowhouse/CONTROL

Source: so5extra  
Version: 1.3.1-1  
Description: A set of additional tools for SObjectizer framework.  
Build-Depends: sobjectizer  
control: vcpkg/ports/so5extra/CONTROL

Source: sobjectizer  
Version: 5.6.1  
Homepage: https://github.com/Stiffstream/sobjectizer  
Description: SObjectizer is a C++ in-process message dispatching framework with implementation of Actor Model, Publish-Subscribe Model and CSP-like channels.  
control: vcpkg/ports/sobjectizer/CONTROL

Source: soci  
Version: 3.2.3-4  
Homepage: https://github.com/SOCI/soci  
Description: SOCI database access library  
  
Feature: boost  
Build-Depends: boost-date-time, boost-fusion, boost-optional, boost-preprocessor, boost-tuple  
Description: Integration with Boost  
  
Feature: sqlite3  
Build-Depends: sqlite3  
Description: Build sqlite3 backend  
  
Feature: postgresql  
Build-Depends: libpq  
Description: Build postgresql backend  
  
Feature: odbc  
Description: Build odbc backend  
control: vcpkg/ports/soci/CONTROL

Source: socket-io-client  
Version: 1.6.1-1  
Description: C++11 implementation of Socket.IO client  
Build-Depends: boost, rapidjson, websocketpp  
control: vcpkg/ports/socket-io-client/CONTROL

Source: soil  
Version: 2008.07.07-1  
Description: Simple OpenGL Image Library  
control: vcpkg/ports/soil/CONTROL

Source: soil2  
Version: release-1.11  
Description: Simple OpenGL Image Library 2  
control: vcpkg/ports/soil2/CONTROL

Source: sokol  
Version: 2019-09-09  
Description: Minimal cross-platform standalone C headers  
Homepage: https://github.com/floooh/sokol  
control: vcpkg/ports/sokol/CONTROL

Source: sol2  
Version: 3.0.3-1  
Homepage: https://github.com/ThePhD/sol2  
Description: Sol v2.0 - a C++ <-> Lua API wrapper with advanced features and top notch performance - is here, and it's great  
Build-Depends: lua (windows)  
control: vcpkg/ports/sol2/CONTROL

Source: solid3  
Version: 3.5.8  
Description: Software Library for Interference Detection  
control: vcpkg/ports/solid3/CONTROL

Source: sophus  
Version: 1.0.0-6  
Build-Depends: eigen3, ceres, suitesparse  
Homepage: https://github.com/strasdat/Sophus  
Description: Lie group library for C++  
control: vcpkg/ports/sophus/CONTROL

Source: soundtouch  
Version: 2.0.0-3  
Homepage: https://www.surina.net/soundtouch  
Description: SoundTouch is an open-source audio processing library for changing the Tempo, Pitch and Playback Rates of audio streams or audio files.  
Build-Depends: atlmfc (windows)  
control: vcpkg/ports/soundtouch/CONTROL

Source: soxr  
Version: 0.1.3.  
Description: High quality audio resampling  
control: vcpkg/ports/soxr/CONTROL

Source: spaceland  
Version: 7.8.2-3  
Description: Spaceland Lib (sl) is a suite for geometric computation, specifically adapted to OpenGL.  
Build-Depends: zlib  
control: vcpkg/ports/spaceland/CONTROL

Source: span-lite  
Version: 0.5.0  
Description: A C++20-like span for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/span-lite/CONTROL

Source: sparsehash  
Version: 2.0.3  
Homepage: https://github.com/sparsehash/sparsehash  
Description: The sparsehash package consists of two hashtable implementations: sparse, which is designed to be very space efficient, and dense, which is designed to be very time efficient.  
control: vcpkg/ports/sparsehash/CONTROL

Source: sparsepp  
Version: 1.22-1  
Description: A fast, memory efficient hash map for C++  
control: vcpkg/ports/sparsepp/CONTROL

Source: spatialite-tools  
Version: 4.3.0-1  
Homepage: https://www.gaia-gis.it/fossil/spatialite-tools/index  
Description: Contains spatialite.exe and other command line tools to work with SpatiaLite databases (import, export, SQL queries)  
Build-Depends: sqlite3, libspatialite, geos, readosm, proj4, zlib, libiconv, expat  
control: vcpkg/ports/spatialite-tools/CONTROL

Source: spdk  
Version: 19.01.1  
Description: Storage Performance Development Kit  
Build-Depends: spdk-dpdk, spdk-ipsec, spdk-isal  
control: vcpkg/ports/spdk/CONTROL

Source: spdk-dpdk  
Version: 20181124  
Description: SPDK mirror of DPDK. A set of libraries and drivers for fast packet processing  
  
control: vcpkg/ports/spdk-dpdk/CONTROL

Source: spdk-ipsec  
Version: 20180711  
Description: SPDK mirror of ipsec. Intel(R) Multi-Buffer Crypto for IPsec Library  
  
control: vcpkg/ports/spdk-ipsec/CONTROL

Source: spdk-isal  
Version: 20181006  
Description: SPDK mirror of isa-l. Intel(R) Intelligent Storage Acceleration Library  
  
control: vcpkg/ports/spdk-isal/CONTROL

Source: spdlog  
Version: 1.3.1-2  
Homepage: https://github.com/gabime/spdlog  
Description: Very fast, header only, C++ logging library  
Build-Depends: fmt  
  
Feature: benchmark  
Description: Use google benchmark  
Build-Depends: benchmark  
control: vcpkg/ports/spdlog/CONTROL

Source: spectra  
Version: 0.8.1  
Description: A header-only C++ library for large scale eigenvalue problems  
Homepage: https://spectralib.org  
Build-Depends: eigen3  
control: vcpkg/ports/spectra/CONTROL

Source: speex  
Version: 1.2.0-4  
Homepage: https://github.com/xiph/speex  
Description: Speex is an Open Source/Free Software patent-free audio compression format designed for speech.  
control: vcpkg/ports/speex/CONTROL

Source: speexdsp  
Version: 1.2.0  
Homepage: https://ftp.osuosl.org/pub/xiph/releases/speex/  
Description: A patent-free, Open Source/Free Software DSP library.  
Build-Depends:  
control: vcpkg/ports/speexdsp/CONTROL

Source: spirit-po  
Version: 1.1.2-1  
Homepage: https://github.com/cbeck88/spirit-po  
Description: A header-only C++ library for localization using GNU gettext po files, based on Boost.Spirit.  
Build-Depends: boost  
control: vcpkg/ports/spirit-po/CONTROL

Source: spirv-cross  
Version: 2019-07-26  
Description: SPIRV-Cross is a practical tool and library for performing reflection on SPIR-V and disassembling SPIR-V back to high level languages.  
control: vcpkg/ports/spirv-cross/CONTROL

Source: spirv-headers  
Version: 2019-05-05  
Description: Machine-readable files for the SPIR-V Registry  
control: vcpkg/ports/spirv-headers/CONTROL

Source: spirv-tools  
Version: 2019.3-dev-1  
Homepage: https://github.com/KhronosGroup/SPIRV-Tools  
Description: API and commands for processing SPIR-V modules  
Build-Depends: spirv-headers  
control: vcpkg/ports/spirv-tools/CONTROL

Source: sprout  
Version: 2019-06-20  
Homepage: https://github.com/bolero-MURAKAMI/Sprout  
Description: C++11/14 constexpr based Containers, Algorithms, Random numbers, Parsing, Ray tracing, Synthesizer, and others  
Build-Depends: boost-array, boost-mpl  
control: vcpkg/ports/sprout/CONTROL

Source: spscqueue  
Version: 2019-07-26  
Description: A bounded single-producer single-consumer wait-free and lock-free queue written in C++11  
Homepage: https://github.com/rigtorp/SPSCQueue  
control: vcpkg/ports/spscqueue/CONTROL

Source: sqlite-modern-cpp  
Version: 3.2-936cd0c8  
Build-Depends: sqlite3  
Homepage: https://github.com/aminroosta/sqlite_modern_cpp  
Description: The C++14 wrapper around sqlite library  
control: vcpkg/ports/sqlite-modern-cpp/CONTROL

Source: sqlite-orm  
Version: 1.4  
Build-Depends: sqlite3  
Description: SQLite ORM light header only library for modern C++  
control: vcpkg/ports/sqlite-orm/CONTROL

Source: sqlite3  
Version: 3.29.0-1  
Homepage: https://sqlite.org/  
Description: SQLite is a software library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine.  
  
Feature: tool  
Description: sqlite3 executable  
control: vcpkg/ports/sqlite3/CONTROL

Source: sqlitecpp  
Version: 2.3.0  
Build-Depends: sqlite3  
Homepage: https://github.com/SRombauts/SQLiteCpp  
Description: SQLiteC++ (SQLiteCpp) is a smart and easy to use C++ SQLite3 wrapper.  
control: vcpkg/ports/sqlitecpp/CONTROL

Source: sqlpp11  
Version: 0.58-1  
Description: A type safe embedded domain specific language for SQL queries and results in C++.  
Build-Depends: date  
control: vcpkg/ports/sqlpp11/CONTROL

Source: sqlpp11-connector-mysql  
Version: 0.25-2  
Description: A C++ wrapper for MySQL meant to be used in combination with sqlpp11.  
Build-Depends: date, libmariadb, sqlpp11  
control: vcpkg/ports/sqlpp11-connector-mysql/CONTROL

Source: sqlpp11-connector-sqlite3  
Version: 0.29-2  
Description: A C++ wrapper for sqlite3 meant to be used in combination with sqlpp11.  
Build-Depends: date, sqlite3, sqlpp11  
control: vcpkg/ports/sqlpp11-connector-sqlite3/CONTROL

Source: status-value-lite  
Version: 1.1.0  
Homepage: https://github.com/martinmoene/status-value-lite  
Description: status_value is a single-file header-only library for objects that represent a status and an optional value. It is intended for use with C++11 and later.   
  
Feature: test  
Description: Build with test  
control: vcpkg/ports/status-value-lite/CONTROL

Source: stb  
Version: 2019-07-11  
Homepage: https://github.com/nothings/stb  
Description: stb single-file public domain libraries for C/C++  
control: vcpkg/ports/stb/CONTROL

Source: stlab  
Version: 1.4.1-1  
Description:   
  stlab is the ongoing work of what was Adobe’s Software Technology Lab.  
  The Concurrency library provides futures and channels, high level constructs for implementing algorithms that eases the use of multiple CPU cores while minimizing contention. This library solves several problems of the C++11 and C++17 TS futures.  
Build-Depends: boost-variant (osx)  
control: vcpkg/ports/stlab/CONTROL

Source: stormlib  
Version: 2019-05-10  
Build-Depends: zlib, bzip2  
Description: StormLib is a library for opening and manipulating Blizzard MPQ files  
control: vcpkg/ports/stormlib/CONTROL

Source: strict-variant  
Version: 0.5  
Description: Tagged union implementation that will never throw an exception or make a dynamic allocation in the effort of supporting types that have throwing moves.  
control: vcpkg/ports/strict-variant/CONTROL

Source: string-theory  
Version: 2.2  
Homepage: https://github.com/zrax/string_theory  
Description: Flexible C++11 string library with type-safe formatting.  
control: vcpkg/ports/string-theory/CONTROL

Source: string-view-lite  
Version: 1.3.0  
Description: A C++17-like string_view for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/string-view-lite/CONTROL

Source: strtk  
Version: 2019-01-09  
Homepage: https://github.com/ArashPartow/strtk  
Description: robust, optimized and portable string processing algorithms for the C++ language  
Build-Depends: boost  
control: vcpkg/ports/strtk/CONTROL

Source: stxxl  
Version: 2018-11-15-2  
Description: Standard Template Library for Extra Large Data Sets  
control: vcpkg/ports/stxxl/CONTROL

Source: suitesparse  
Version: 5.4.0-3  
Build-Depends: clapack (!osx)  
Homepage: http://faculty.cse.tamu.edu/davis/SuiteSparse  
Description: algebra library  
  
Feature: metis  
Build-Depends: metis  
Description: Use metis in SuiteSparse  
control: vcpkg/ports/suitesparse/CONTROL

Source: sundials  
Version: 3.1.1-1  
Homepage: https://computation.llnl.gov/projects/sundials  
Description: SUNDIALS (SUite of Nonlinear and DIfferential/ALgebraic equation Solvers)  
control: vcpkg/ports/sundials/CONTROL

Source: systemc  
Version: 2.3.3-3  
Description: A set of C++ classes and macros which provide an event-driven simulation kernel in C++  
control: vcpkg/ports/systemc/CONTROL

Source: szip  
Version: 2.1.1-5  
Homepage: https://support.hdfgroup.org/ftp/lib-external/szip  
Description: Szip compression software, providing lossless compression of scientific data  
control: vcpkg/ports/szip/CONTROL

Source: tacopie  
Version: 3.2.0-2  
Homepage: https://github.com/cpp-redis/tacopie  
Description: Tacopie is a TCP Client & Server C++11 library  
control: vcpkg/ports/tacopie/CONTROL

Source: taglib  
Version: 1.11.1-20190531  
Description: TagLib Audio Meta-Data Library  
Homepage: https://github.com/taglib/taglib  
Build-Depends: zlib  
control: vcpkg/ports/taglib/CONTROL

Source: taocpp-json  
Version: 2019-07-11  
Description: C++ header-only JSON library  
control: vcpkg/ports/taocpp-json/CONTROL

Source: tap-windows6  
Version: 9.21.2-0e30f5c  
Description: an NDIS 6 implementation of the TAP-Windows driver, used by OpenVPN and other apps. Note: This package only contains the headers for the driver.  
control: vcpkg/ports/tap-windows6/CONTROL

Source: tbb  
Version: 2019_U8-1  
Homepage: https://github.com/01org/tbb  
Description: Intel's Threading Building Blocks.  
control: vcpkg/ports/tbb/CONTROL

Source: tcl  
Version: 8.6.5  
Homepage: https://github.com/tcltk/tcl  
Description: Tcl provides a powerful platform for creating integration applications that tie together diverse applications, protocols, devices, and frameworks. When paired with the Tk toolkit, Tcl provides the fastest and most powerful way to create GUI applications that run on PCs, Unix, and Mac OS X. Tcl can also be used for a variety of web-related tasks and for creating powerful command languages for applications.  
control: vcpkg/ports/tcl/CONTROL

Source: tclap  
Version: 1.2.2  
Homepage: https://sourceforge.net/projects/tclap/  
Description: Templatized command-line argument parser for C++  
control: vcpkg/ports/tclap/CONTROL

Source: telnetpp  
Version: 2.0-2  
Homepage: https://github.com/KazDragon/telnetpp  
Description: Telnet++ is an implementation of the Telnet Session Layer protocol using C++14  
Build-Depends: boost-container, boost-signals2, boost-variant, gtest, gsl-lite, boost-exception  
Default-Features: zlib  
  
Feature: zlib  
Description: Zlib support  
Build-Depends: zlib  
control: vcpkg/ports/telnetpp/CONTROL

Source: tensorflow-cc  
Version: 1.14-1  
Description: Library for computation using data flow graphs for scalable machine learning  
Build-Depends: c-ares  
control: vcpkg/ports/tensorflow-cc/CONTROL

Source: tesseract  
Version: 4.1.0-2  
Homepage: https://github.com/tesseract-ocr/tesseract  
Description: An OCR Engine that was developed at HP Labs between 1985 and 1995... and now at Google.  
Build-Depends: leptonica  
  
Feature: training_tools  
Description: build training tools  
Build-Depends: icu, pango, cairo, fontconfig  
  
Feature: cpu_independed  
Description: build on any cpu extension commands support  
control: vcpkg/ports/tesseract/CONTROL

Source: tgc  
Version: 2019-08-11  
Description: A tiny garbage collector for C  
Homepage: https://github.com/orangeduck/tgc  
control: vcpkg/ports/tgc/CONTROL

Source: tgui  
Version: 0.8.5  
Description: TGUI is an easy to use, cross-platform, C++ GUI for SFML.  
Build-Depends: sfml  
  
Feature: tool  
Description: Build GUI builder  
control: vcpkg/ports/tgui/CONTROL

Source: theia  
Version: 0.8-2  
Build-Depends: flann, cereal, ceres[suitesparse], openimageio, glew, freeglut (!osx)  
Homepage: https://github.com/sweeneychris/TheiaSfM  
Description: An open source library for multiview geometry and structure from motion  
control: vcpkg/ports/theia/CONTROL

Source: think-cell-range  
Maintainer: jfrederich@gmail.com  
Version: 498839d-1  
Description: think-cell's range library  
Homepage: https://github.com/think-cell/range  
Build-Depends: boost  
control: vcpkg/ports/think-cell-range/CONTROL

Source: thor  
Version: 2.0-3  
Description: Extends the multimedia library SFML with higher-level features  
Build-Depends: sfml, aurora  
control: vcpkg/ports/thor/CONTROL

Source: thrift  
Version: 2019-05-07-4  
Build-Depends: zlib, libevent, openssl, boost-range, boost-smart-ptr, boost-date-time, boost-locale, boost-scope-exit  
Homepage: https://github.com/apache/thrift  
Description: Apache Thrift is a software project spanning a variety of programming languages and use cases. Our goal is to make reliable, performant communication and data serialization across languages as efficient and seamless as possible.  
control: vcpkg/ports/thrift/CONTROL

Source: tidy-html5  
Version: 5.7.28  
Homepage: https://github.com/htacg/tidy-html5  
Description: Tidy tidies HTML and XML. It can tidy your documents by itself, and developers can easily integrate its features into even more powerful tools.  
control: vcpkg/ports/tidy-html5/CONTROL

Source: tiff  
Version: 4.0.10-7  
Build-Depends: zlib, libjpeg-turbo, liblzma  
Homepage: https://download.osgeo.org/libtiff  
Description: A library that supports the manipulation of TIFF image files  
control: vcpkg/ports/tiff/CONTROL

Source: tinkerforge  
Version: 2.1.25  
Description: Tinkerforge C API bindings for bricks and bricklets  
control: vcpkg/ports/tinkerforge/CONTROL

Source: tiny-aes-c  
Version: 2019-07-31  
Description: Small portable AES128/192/256 in C  
Homepage: https://github.com/kokke/tiny-AES-c  
control: vcpkg/ports/tiny-aes-c/CONTROL

Source: tiny-bignum-c  
Version: 2019-07-31  
Description: Small portable multiple-precision unsigned integer arithmetic in C  
Homepage: https://github.com/kokke/tiny-bignum-c  
control: vcpkg/ports/tiny-bignum-c/CONTROL

Source: tiny-dnn  
Version: 2018-10-25  
Homepage: https://github.com/tiny-dnn/tiny-dnn  
Description: A C++14 implementation of deep learning. It is suitable for deep learning on limited computational resource.  
control: vcpkg/ports/tiny-dnn/CONTROL

Source: tiny-process-library  
Version: 2018-12-06  
Description: A small platform independent library  
control: vcpkg/ports/tiny-process-library/CONTROL

Source: tiny-regex-c  
Version: 2019-07-31  
Description: A small regex implementation in C  
Homepage: https://github.com/kokke/tiny-regex-c  
control: vcpkg/ports/tiny-regex-c/CONTROL

Source: tinycthread  
Version: 2019-08-06  
Description: Small, portable implementation of the C11 threads API  
Homepage: https://tinycthread.github.io/  
control: vcpkg/ports/tinycthread/CONTROL

Source: tinydir  
Version: 1.2.4  
Homepage: https://github.com/cxong/tinydir  
Description: Lightweight, portable and easy to integrate C directory and file reader  
control: vcpkg/ports/tinydir/CONTROL

Source: tinyexif  
Version: 1.0.2-6  
Build-Depends: tinyxml2  
Homepage: https://github.com/cdcseacave/TinyEXIF  
Description: tiny ISO-compliant C++ EXIF and XMP parsing library for JPEG images  
control: vcpkg/ports/tinyexif/CONTROL

Source: tinyexr  
Version: 0.9.5-d16ea6-1  
Homepage: https://github.com/syoyo/tinyexr  
Description: Library to load and save OpenEXR(.exr) images  
control: vcpkg/ports/tinyexr/CONTROL

Source: tinyfiledialogs  
Version: 3.3.8  
Description: Highly portable and cross-platform dialogs for native inputbox, passwordbox, colorpicker and more  
control: vcpkg/ports/tinyfiledialogs/CONTROL

Source: tinygltf  
Version: 2.2.0  
Description: A header only C++11 glTF 2.0 library.  
Build-Depends: stb, nlohmann-json  
control: vcpkg/ports/tinygltf/CONTROL

Source: tinynpy  
Version: 1.0.0-3  
Build-Depends: zlib  
Description: tiny C++ loader/exporter of python numpy array NPY/NPZ files  
control: vcpkg/ports/tinynpy/CONTROL

Source: tinyobjloader  
Version: 1.0.7-1  
Description: Tiny but powerful single file wavefront obj loader  
control: vcpkg/ports/tinyobjloader/CONTROL

Source: tinyspline  
Version: 0.2.0-3  
Description: Library for NURBS, B-Splines, and B?zier curves, allowing you to handle splines with ease  
control: vcpkg/ports/tinyspline/CONTROL

Source: tinythread  
Version: 1.1-2  
Homepage: https://tinythreadpp.bitsnbites.eu/  
Description: Implements a fairly compatible subset of the C++11 thread management classes  
control: vcpkg/ports/tinythread/CONTROL

Source: tinytoml  
Version: 20180219-1  
Homepage: https://github.com/mayah/tinytoml  
Description: A header only C++11 library for parsing TOML.  
control: vcpkg/ports/tinytoml/CONTROL

Source: tinyutf8  
Version: 3.0.1  
Description: TINYUTF8 is a library for extremely easy integration of Unicode into an arbitrary C++11 project.  
control: vcpkg/ports/tinyutf8/CONTROL

Source: tinyxml  
Version: 2.6.2-4  
Homepage: https://sourceforge.net/projects/tinyxml  
Description: A simple, small, minimal, C++ XML parser that can be easily integrating into other programs.  
control: vcpkg/ports/tinyxml/CONTROL

Source: tinyxml2  
Version: 7.0.1-2  
Homepage: https://github.com/leethomason/tinyxml2  
Description: A simple, small, efficient, C++ XML parser  
  
control: vcpkg/ports/tinyxml2/CONTROL

Source: tl-expected  
Version: 1.0.0-1  
Description: C++11/14/17 std::expected implementation with functional-style extensions   
control: vcpkg/ports/tl-expected/CONTROL

Source: tl-function-ref  
Version: 1.0.0-1  
Description: A lightweight, non-owning reference to a callable.  
control: vcpkg/ports/tl-function-ref/CONTROL

Source: tl-optional  
Version: 1.0.0-1  
Description: C++11/14/17 std::optional implementation with functional-style extensions   
control: vcpkg/ports/tl-optional/CONTROL

Source: tmx  
Version: 1.0.0-1  
Description: A portable C library to load tiled maps in your games.  
Build-Depends: zlib, libxml2  
control: vcpkg/ports/tmx/CONTROL

Source: tmxlite  
Version: 2019-03-05  
Description: A lightweight C++14 parsing library for tmx map files created with the Tiled map editor.  
control: vcpkg/ports/tmxlite/CONTROL

Source: tmxparser  
Version: 2.1.0-2  
Description: C++11 library for parsing the maps generated by the Map Editor called Tiled.  
Build-Depends: zlib, tinyxml2  
control: vcpkg/ports/tmxparser/CONTROL

Source: torch-th  
Version: 2019-04-19-1  
Homepage: https://github.com/torch/torch7  
Description: Torch's TH library  
control: vcpkg/ports/torch-th/CONTROL

Source: tre  
Version: 0.8.0-1  
Homepage: https://github.com/laurikari/tre  
Description: TRE is a lightweight, robust, and efficient POSIX compliant regexp matching library with some exciting features such as approximate (fuzzy) matching.  
control: vcpkg/ports/tre/CONTROL

Source: treehopper  
Version: 1.11.3-3  
Description: Treehopper connects the physical world to your computer, tablet, or smartphone.  
Homepage: https://treehopper.io  
Build-Depends: libusb  
control: vcpkg/ports/treehopper/CONTROL

Source: trompeloeil  
Version: 34-1  
Description: A thread-safe header-only mocking framework for C++11/14 using the Boost Software License 1.0  
Homepage: https://github.com/rollbear/trompeloeil  
control: vcpkg/ports/trompeloeil/CONTROL

Source: tsl-hopscotch-map  
Version: 2.2.1-1  
Description: C++ implementation of a fast hash map and hash set using hopscotch hashing   
control: vcpkg/ports/tsl-hopscotch-map/CONTROL

Source: tsl-ordered-map  
Version: 0.8.1-1  
Description: C++ hash map and hash set which preserve the order of insertion  
control: vcpkg/ports/tsl-ordered-map/CONTROL

Source: tsl-sparse-map  
Version: 0.6.1-1  
Description: C++ implementation of a memory efficient hash map and hash set  
control: vcpkg/ports/tsl-sparse-map/CONTROL

Source: tweeny  
Version: 3.0  
Description: A modern C++ tweening library  
Homepage: https://github.com/mobius3/tweeny  
control: vcpkg/ports/tweeny/CONTROL

Source: type-lite  
Version: 0.1.0  
Homepage: https://github.com/martinmoene/type-lite  
Description: Strong types for C++98, C++11 and later in a single-file header-only library.  
  
Feature: test  
Description: Build with test  
  
  
control: vcpkg/ports/type-lite/CONTROL

Source: umock-c  
Version: 2019-08-20.1  
Description: A pure C mocking library  
Build-Depends: azure-macro-utils-c  
  
control: vcpkg/ports/umock-c/CONTROL

Source: unicorn  
Version: 2019-07-11  
Homepage: https://github.com/unicorn-engine/unicorn  
Description: Unicorn is a lightweight multi-platform, multi-architecture CPU emulator framework  
control: vcpkg/ports/unicorn/CONTROL

Source: unicorn-lib  
Version: 2019-07-11  
Homepage: https://github.com/CaptainCrowbar/unicorn-lib  
Description: Unicode library for C++ by Ross Smith  
Build-Depends: rs-core-lib, pcre2, zlib, libiconv  
control: vcpkg/ports/unicorn-lib/CONTROL

Source: units  
Version: 2.3.0  
Homepage: https://github.com/nholthaus/units  
Description: A compile-time, header-only, dimensional analysis and unit conversion library built on c++14 with no dependencies.   
control: vcpkg/ports/units/CONTROL

Source: unittest-cpp  
Version: 2.0.0-1  
Homepage: https://github.com/unittest-cpp/unittest-cpp  
Description: A lightweight unit testing framework for C++  
control: vcpkg/ports/unittest-cpp/CONTROL

Source: unrar  
Version: 5.8.1  
Homepage: https://www.rarlab.com  
Description: rarlab's unrar libary  
control: vcpkg/ports/unrar/CONTROL

Source: urdfdom  
Version: 1.0.3-1  
Homepage: https://github.com/ros/urdfdom  
Description: Provides core data structures and a simple XML parsers for populating the class data structures from an URDF file.  
Build-Depends: console-bridge, tinyxml, urdfdom-headers  
control: vcpkg/ports/urdfdom/CONTROL

Source: urdfdom-headers  
Version: 1.0.4-1  
Homepage: https://github.com/ros/urdfdom_headers  
Description: The URDF (U-Robot Description Format) headers provides core data structure headers for URDF.  
control: vcpkg/ports/urdfdom-headers/CONTROL

Source: uriparser  
Version: 0.9.3-4  
Homepage: https://github.com/uriparser/uriparser  
Description: uriparser is a strictly RFC 3986 compliant URI parsing and handling library written in C89 ("ANSI C"). uriparser is cross-platform, fast, supports Unicode, and is licensed under the New BSD license.  
  
Feature: tool  
Description: Builds tools (e.g. CLI "uriparse")  
control: vcpkg/ports/uriparser/CONTROL

Source: usbmuxd  
Version: 1.2.76  
Description: A socket daemon to multiplex connections from and to iOS devices  
Build-Depends: libimobiledevice, libusb, libusb-win32, pthreads  
control: vcpkg/ports/usbmuxd/CONTROL

Source: usd  
Version: 0.8.4-2  
Build-Depends: boost-assign, boost-crc, boost-date-time, boost-filesystem, boost-format, boost-multi-index, boost-program-options, boost-regex, boost-system, boost-vmd, tbb, zlib  
Description: Universal Scene Description (USD) is an efficient, scalable system for authoring, reading, and streaming time-sampled scene description for interchange between graphics applications.  
control: vcpkg/ports/usd/CONTROL

Source: usockets  
Version: 0.3.1  
Build-Depends:libuv  
Description: Miniscule cross-platform eventing, networking & crypto for async applications  
control: vcpkg/ports/usockets/CONTROL

Source: usrsctp  
Version: 35c1d97020a-2  
Description: This is a userland SCTP stack supporting FreeBSD, Linux, Mac OS X and Windows.  
control: vcpkg/ports/usrsctp/CONTROL

Source: utf8h  
Version: 841cb2deb8eb806e73fff0e1f43a11fca4f5da45  
Description: Single header utf8 string functions for C and C++  
control: vcpkg/ports/utf8h/CONTROL

Source: utf8proc  
Version: 2.4.0  
Homepage: https://github.com/JuliaLang/utf8proc  
Description: Clean C library for processing UTF-8 Unicode data.  
control: vcpkg/ports/utf8proc/CONTROL

Source: utfcpp  
Version: 3.1  
Homepage: https://github.com/nemtrif/utfcpp  
Description: UTF-8 with C++ in a Portable Way  
control: vcpkg/ports/utfcpp/CONTROL

Source: utfz  
Version: 1.2-1  
Homepage: https://github.com/IMQS/utfz  
Description: A tiny C++ library for parsing and encoding utf-8  
control: vcpkg/ports/utfz/CONTROL

Source: uvatlas  
Version: apr2019  
Homepage: https://github.com/Microsoft/UVAtlas  
Description: UVAtlas isochart texture atlas  
control: vcpkg/ports/uvatlas/CONTROL

Source: uvw  
Version: 1.18.0  
Description: Header-only, event based, tiny and easy to use libuv wrapper in modern C++.  
Homepage: https://github.com/skypjack/uvw  
Build-Depends: libuv  
control: vcpkg/ports/uvw/CONTROL

Source: uwebsockets  
Version: 0.15.7  
Build-Depends: zlib, usockets  
Homepage: https://github.com/uWebSockets/uWebSockets  
Description: Simple, secure & standards compliant web I/O for the most demanding of applications  
control: vcpkg/ports/uwebsockets/CONTROL

Source: valijson  
Version: 2018-11-17  
Description: Header-only C++ library for JSON Schema validation  
control: vcpkg/ports/valijson/CONTROL

Source: value-ptr-lite  
Version: 0.2.1  
Homepage: https://github.com/martinmoene/value-ptr-lite  
Description: A C++ smart-pointer with value semantics for C++98, C++11 and later in a single-file header-only library.   
  
Feature: test  
Description: Build with test  
control: vcpkg/ports/value-ptr-lite/CONTROL

Source: variant-lite  
Version: 1.2.2  
Description: A C++17-like variant, a type-safe union for C++98, C++11 and later in a single-file header-only library  
control: vcpkg/ports/variant-lite/CONTROL

Source: vcglib  
Version: 1.0.1  
Description: library for manipulation, processing, cleaning, simplifying triangle meshes.  
Build-Depends: eigen3  
control: vcpkg/ports/vcglib/CONTROL

Source: vectorclass  
Version: 2.00.01  
Homepage: https://github.com/vectorclass/version2  
Description: C++ class library for using the Single Instruction Multiple Data (SIMD) instructions in modern Microprocessors  
control: vcpkg/ports/vectorclass/CONTROL

Source: visit-struct  
Version: 1.0-1  
Description: A header-only library providing structure visitors for C++11 and C++14  
control: vcpkg/ports/visit-struct/CONTROL

Source: vlpp  
Version: 0.10.0.0  
Homepage: https://github.com/vczh-libraries/Release  
Description: Common C++ construction, including string operation / generic container / linq / General-LR parser generator / multithreading / reflection for C++ / etc  
control: vcpkg/ports/vlpp/CONTROL

Source: volk  
Version: 2019-09-26  
Description: Meta loader for Vulkan API.  
  Note that the static library target volk::volk is built without platform-specific defines.  
  Use the header-only target volk::volk_headers if you require platform-specific extensions.  
Homepage: https://github.com/zeux/volk  
Build-Depends: vulkan  
control: vcpkg/ports/volk/CONTROL

Source: vtk  
Version: 8.2.0-8  
Description: Software system for 3D computer graphics, image processing, and visualization  
Homepage: https://github.com/Kitware/VTK  
Build-Depends: zlib, libpng, tiff, libxml2, jsoncpp, glew, freetype, expat, hdf5, libjpeg-turbo, proj4, lz4, libtheora, atlmfc (windows), eigen3, double-conversion, pugixml, libharu, sqlite3, netcdf-c  
  
Feature: openvr  
Description: OpenVR functionality for VTK  
Build-Depends: sdl2, openvr  
  
Feature: qt  
Description: Qt functionality for VTK  
Build-Depends: qt5  
  
Feature: mpi  
Description: MPI functionality for VTK  
Build-Depends: mpi, hdf5[parallel]  
  
Feature: python  
Description: Python functionality for VTK  
Build-Depends: python3  
control: vcpkg/ports/vtk/CONTROL

Source: vtk-dicom  
Version: 0.8.10  
Description: DICOM for VTK  
Build-Depends: vtk, zlib  
  
Feature: gdcm  
Description: Use gdcm for decompressing DICOM files.  
Build-Depends: gdcm  
control: vcpkg/ports/vtk-dicom/CONTROL

Source: vulkan  
Version: 1.1.82.1-1  
Description: A graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs on a wide variety of devices.  
control: vcpkg/ports/vulkan/CONTROL

Source: vulkan-hpp  
Version: 2019-05-11  
Description: Header only C++ bindings for the Vulkan C API  
Build-Depends: vulkan  
control: vcpkg/ports/vulkan-hpp/CONTROL

Source: vulkan-memory-allocator  
Version: 2.2.0  
Description: Easy to integrate Vulkan memory allocation library from GPUOpen  
control: vcpkg/ports/vulkan-memory-allocator/CONTROL

Source: vxl  
Version: v1.18.0-4  
Build-Depends: bzip2, expat, libgeotiff, libjpeg-turbo, libpng, shapelib, tiff, zlib  
# Build-Depends: bzip2, dcmtk, expat, libgeotiff, libjpeg-turbo, openjpeg, libpng, shapelib, tiff, zlib  
Description: A multi-platform collection of C++ software libraries for Computer Vision and Image Understanding.  
  
Feature: core_imaging  
Description: core_imaging support for vxl  
control: vcpkg/ports/vxl/CONTROL

Source: wampcc  
Build-Depends: openssl, libuv, jansson  
Version: 2019-09-04  
Description: Wampcc is C++ library that implements the Web Application Messaging Protocol (WAMP) protocol.  
  
Feature: utils  
Description: Build utility apps  
  
Feature: examples  
Description: Build example apps  
control: vcpkg/ports/wampcc/CONTROL

Source: wangle  
Version: 2019.07.08.00  
Build-Depends: fizz, folly, openssl, glog, libevent, double-conversion, boost-system, boost-thread, boost-filesystem, boost-regex, boost-context  
Description: Wangle is a framework providing a set of common client/server abstractions for building services in a consistent, modular, and composable way.  
control: vcpkg/ports/wangle/CONTROL

Source: wavpack  
Version: 5.1.0-2  
Homepage: https://github.com/dbry/WavPack  
Description: WavPack encode/decode library, command-line programs, and several plugins  
control: vcpkg/ports/wavpack/CONTROL

Source: websocketpp  
Version: 0.8.1-1  
Build-Depends: zlib, openssl, boost-asio  
Homepage: https://github.com/zaphoyd/websocketpp  
Description: Library that implements RFC6455 The WebSocket Protocol  
control: vcpkg/ports/websocketpp/CONTROL

Source: wepoll  
Version: 1.5.5  
Description: Fast epoll for windows  
Homepage: https://github.com/piscisaureus/wepoll  
control: vcpkg/ports/wepoll/CONTROL

Source: wg21-sg14  
Version: 2019-08-13  
Description: A library for Study Group 14 of Working Group 21 (C++)  
Homepage: https://github.com/WG21-SG14/SG14  
control: vcpkg/ports/wg21-sg14/CONTROL

Source: wil  
Version: 2019-07-16  
Description: The Windows Implementation Libraries (WIL) is a header-only C++ library created to make life easier for developers on Windows through readable type-safe C++ interfaces for common Windows coding patterns.  
control: vcpkg/ports/wil/CONTROL

Source: wildmidi  
Version: 0.4.3  
Homepage: https://github.com/Mindwerks/wildmidi  
Description: MIDI software synthesizer library.  
control: vcpkg/ports/wildmidi/CONTROL

Source: wincrypt  
Version: 0.0-1  
Description: Windows Cryptography.  
control: vcpkg/ports/wincrypt/CONTROL

Source: winpcap  
Version: 4.1.3-2  
Homepage: https://www.winpcap.org  
Description: WinPcap is the industry-standard tool for link-layer network access in Windows environments.  
control: vcpkg/ports/winpcap/CONTROL

Source: winreg  
Version: 1.2.1-1  
Homepage: https://github.com/GiovanniDicanio/WinReg  
Description: High-level C++ wrapper around the Windows Registry C API.  
control: vcpkg/ports/winreg/CONTROL

Source: winsock2  
Version: 0.0-1  
Description: Windows Sockets.  
control: vcpkg/ports/winsock2/CONTROL

Source: wintoast  
Version: 1.2.0  
Description: WinToast is a lightly library written in C++ which brings a complete integration of the modern toast notifications of Windows 8 & Windows 10.  
control: vcpkg/ports/wintoast/CONTROL

Source: woff2  
Version: 1.0.2  
Build-Depends: brotli  
Description: font compression reference code  
control: vcpkg/ports/woff2/CONTROL

Source: wpilib  
Version: 2019.6.1  
Build-Depends: eigen3, libuv  
Description: WPILib is the software library package for the FIRST Robotics Competition. The core install includes wpiutil, a common utilies library, and ntcore, the base NetworkTables library.  
  
Feature: cameraserver  
Build-Depends: opencv  
Description: Enables the CameraServer and CSCore libraries for manipulating USB Cameras and HTTP Camera Streams  
  
Feature: allwpilib  
Build-Depends: wpilib[cameraserver], opencv  
Description: Enables the simulation HAL, and the high level wpilibc library.  
control: vcpkg/ports/wpilib/CONTROL

Source: wren  
Version: 2019-07-01  
Homepage: https://github.com/wren-lang/wren  
Description: Wren is a small, fast, class-based concurrent scripting language.  
control: vcpkg/ports/wren/CONTROL

Source: wt  
Version: 4.0.5-1  
Homepage: https://github.com/emweb/wt  
Description: Wt is a C++ library for developing web applications  
Build-Depends: openssl, sqlite3, libpq, pango, glew, boost-date-time, boost-regex, boost-program-options, boost-signals, boost-system, boost-filesystem, boost-thread, boost-random, boost-multi-index, boost-signals2, boost-asio, boost-ublas, boost-conversion, boost-array, boost-smart-ptr, boost-tuple, boost-algorithm, boost-logic, boost-interprocess  
control: vcpkg/ports/wt/CONTROL

Source: wtl  
Maintainer: jfrederich@gmail.com  
Version: 10.0-3  
Homepage: https://sourceforge.net/projects/wtl/  
Description: Windows Template Library (WTL) is a C++ library for developing Windows applications and UI components.  
Build-Depends:  
control: vcpkg/ports/wtl/CONTROL

Source: wxwidgets  
Version: 3.1.2-2  
Homepage: https://github.com/wxWidgets/wxWidgets  
Description: wxWidgets is a widget toolkit and tools library for creating graphical user interfaces (GUIs) for cross-platform applications.  
Build-Depends: zlib, libpng, tiff, expat  
control: vcpkg/ports/wxwidgets/CONTROL

Source: x-plane  
Version: 3.0.1  
Description: The X-Plane Plugin SDK.  
control: vcpkg/ports/x-plane/CONTROL

Source: x264  
Version: 157-303c484ec828ed0-2  
Homepage: https://github.com/mirror/x264  
Description: x264 is a free software library and application for encoding video streams into the H.264/MPEG-4 AVC compression format  
control: vcpkg/ports/x264/CONTROL

Source: x265  
Version: 3.0-1  
Homepage: https://bitbucket.org/multicoreware/x265  
Description: x265 is a H.265 / HEVC video encoder application library, designed to encode video or images into an H.265 / HEVC encoded bitstream.  
control: vcpkg/ports/x265/CONTROL

Source: xalan-c  
Version: 1.11-8  
Homepage: https://github.com/apache/xalan-c  
Description: Xalan is an XSLT processor for transforming XML documents into HTML, text, or other XML document types  
Build-Depends: xerces-c  
control: vcpkg/ports/xalan-c/CONTROL

Source: xerces-c  
Version: 3.2.2-11  
Homepage: https://github.com/apache/xerces-c  
Description: Xerces-C++ is a XML parser, for parsing, generating, manipulating, and validating XML documents using the DOM, SAX, and SAX2 APIs.  
  
Feature: icu  
Description: ICU support  
Build-Depends: icu  
  
Feature: xmlch_wchar  
Description: XMLCh type uses wchar_t  
  
control: vcpkg/ports/xerces-c/CONTROL

Source: xeus  
Version: 0.20.0  
Description: C++ implementation of the Jupyter kernel protocol  
Build-Depends: cppzmq, libuuid (linux), nlohmann-json, openssl, xtl, zeromq  
control: vcpkg/ports/xeus/CONTROL

Source: xlnt  
Version: 1.3.0-2  
Homepage: https://github.com/tfussell/xlnt  
Description: Cross-platform user-friendly xlsx library for C++14  
control: vcpkg/ports/xlnt/CONTROL

Source: xmlsec  
Version: 1.2.28  
Homepage: https://www.aleksey.com/xmlsec/  
Description: XML Security Library is a C library based on LibXML2. The library supports major XML security standards.  
Build-Depends: libxml2, openssl  
control: vcpkg/ports/xmlsec/CONTROL

Source: xmsh  
Version: 0.4.1  
Description: Reference Implementation of XMSH Library  
Build-Depends: tl-expected  
control: vcpkg/ports/xmsh/CONTROL

Source: xorstr  
Version: 2019-08-10  
Description: Heavily vectorized c++17 compile time string encryption  
Homepage: https://github.com/JustasMasiulis/xorstr  
control: vcpkg/ports/xorstr/CONTROL

Source: xproperty  
Version: 0.8.1  
Build-Depends: xtl  
Description: Traitlets-like C++ properties and implementation of the observer pattern  
control: vcpkg/ports/xproperty/CONTROL

Source: xsimd  
Version: 7.2.5  
Description: Modern, portable C++ wrappers for SIMD intrinsics  
Homepage: https://github.com/QuantStack/xsimd  
  
Feature: xcomplex  
Description: xtl complex support  
Build-Depends: xtl  
control: vcpkg/ports/xsimd/CONTROL

Source: xtensor  
Version: 0.20.8  
Description: C++ tensors with broadcasting and lazy computing  
Homepage: https://quantstack.net/xtensor  
Build-Depends: nlohmann-json, xtl  
  
Feature: xsimd  
Description: xtensor with xsimd support  
Build-Depends: xsimd  
  
Feature: tbb  
Description: xtensor with tbb support  
Build-Depends: tbb  
control: vcpkg/ports/xtensor/CONTROL

Source: xtensor-blas  
Version: 0.16.1  
Description: BLAS extension to xtensor  
Build-Depends: xtensor  
control: vcpkg/ports/xtensor-blas/CONTROL

Source: xtensor-io  
Version: 0.7.0  
Description: xtensor plugin to read and write images, audio files, numpy (compressed) npz and HDF5  
Build-Depends: xtensor, xtl  
  
control: vcpkg/ports/xtensor-io/CONTROL

Source: xtl  
Version: 0.6.5  
Build-Depends: nlohmann-json  
Description: The x template library.  
control: vcpkg/ports/xtl/CONTROL

Source: xxhash  
Version: 0.7.0  
Homepage: https://github.com/Cyan4973/xxHash  
Description: Extremely fast hash algorithm  
control: vcpkg/ports/xxhash/CONTROL

Source: yajl  
Version: 2.1.0-1  
Description: Yet Another JSON Library  
control: vcpkg/ports/yajl/CONTROL

Source: yaml-cpp  
Version: 0.6.2-3  
Homepage: https://github.com/jbeder/yaml-cpp  
Description: yaml-cpp is a YAML parser and emitter in C++ matching the YAML 1.2 spec.  
control: vcpkg/ports/yaml-cpp/CONTROL

Source: yara  
Version: 3.10.0  
Homepage: https://github.com/VirusTotal/yara  
Description: The pattern matching swiss knife  
Build-Depends: openssl, jansson  
control: vcpkg/ports/yara/CONTROL

Source: yasm  
Version: 1.3.0  
Homepage: https://github.com/yasm/yasm  
Description: Yasm is a complete rewrite of the NASM assembler under the “new” BSD License.  
control: vcpkg/ports/yasm/CONTROL

Source: yato  
Version: 1.0-2  
Description: Modern C++14 containers and utilities, actors system, typesafe config  
control: vcpkg/ports/yato/CONTROL

Source: yoga  
Version: 1.14.0  
Homepage: https://github.com/facebook/yoga  
Description: Yoga is a cross-platform layout engine which implements Flexbox  
control: vcpkg/ports/yoga/CONTROL

Source: z3  
Version: 4.8.5-1  
Description: An SMT solver  
control: vcpkg/ports/z3/CONTROL

Source: z85  
Version: 1.0  
Description: Z85 is a binary-to-text encoding library. It implements ZeroMQ Base-85 Encoding Algorithm and provides custom padding.  
control: vcpkg/ports/z85/CONTROL

Source: zeromq  
Version: 2019-09-20  
Homepage: https://github.com/zeromq/libzmq  
Description: The ZeroMQ lightweight messaging kernel is a library which extends the standard socket interfaces with features traditionally provided by specialised messaging middleware products  
  
Feature: sodium  
Description: Using libsodium for CURVE security  
Build-Depends: libsodium  
  
Feature: websockets-sha1  
Description: Enable WebSocket transport through builtin sha1 (libzmq#3676)  
control: vcpkg/ports/zeromq/CONTROL

Source: zfp  
Version: 0.5.5-1  
Homepage: https://github.com/LLNL/zfp  
Description: Zfp is an open source C/C++ library for compressed numerical arrays that support high throughput read and write random access. zfp also supports streaming compression of integer and floating-point data, e.g., for applications that read and write large data sets to and from disk. zfp is primarily written in C and C++ but also includes Python and Fortran bindings.  
  
Feature: all  
Description: Build all components  
  
Feature: cfp  
Description: cfp support for cfp  
  
Feature: test  
Description: Build test  
  
Feature: example  
Description: Build example  
  
Feature: utility  
Description: Build utility  
control: vcpkg/ports/zfp/CONTROL

Source: zlib  
Version: 1.2.11-5  
Homepage: https://www.zlib.net/  
Description: A compression library  
control: vcpkg/ports/zlib/CONTROL

Source: zookeeper  
Version: 3.5.5  
Description: ZooKeeper C bindings  
Default-Features: sync  
  
Feature: sync  
Description: ZooKeeper with the sync API  
control: vcpkg/ports/zookeeper/CONTROL

Source: zopfli  
Version: 2019-01-19-1  
Description: Zopfli Compression Algorithm compression library programmed in C  
control: vcpkg/ports/zopfli/CONTROL

Source: zserge-webview  
Version: 2019-04-27-2  
Description: Tiny cross-platform webview library for C/C++/Golang.  
control: vcpkg/ports/zserge-webview/CONTROL

Source: zstd  
Version: 1.4.0  
Description: Zstandard - Fast real-time compression algorithm  
Homepage: https://facebook.github.io/zstd/  
control: vcpkg/ports/zstd/CONTROL

Source: zstr  
Version: 1.0.1  
Description: This C++ header-only library enables the use of C++ standard iostreams to access ZLib-compressed streams.  
control: vcpkg/ports/zstr/CONTROL

Source: zxing-cpp  
Version: 3.3.3-6  
Build-Depends: opencv  
Description: Barcode detection and decoding library.  
control: vcpkg/ports/zxing-cpp/CONTROL

Source: zydis  
Version: 2.0.3  
Description: Fast and lightweight x86/x86-64 disassembler library.  
control: vcpkg/ports/zydis/CONTROL

Source: zyre  
Version: 2019-07-07  
Build-Depends: czmq  
Description: An open-source framework for proximity-based peer-to-peer applications  
Homepage: https://github.com/zeromq/zyre  
control: vcpkg/ports/zyre/CONTROL

Source: zziplib  
Version: 0.13.69-4  
Build-Depends: zlib  
Homepage: https://github.com/gdraheim/zziplib  
Description: library providing read access on ZIP-archives  
control: vcpkg/ports/zziplib/CONTROL

