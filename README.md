# gRPC metapackage
<p align="center">
<a href="https://github.com/zingimmick/grpc-metapackage/actions"><img src="https://github.com/zingimmick/grpc-metapackage/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/zing/grpc-metapackage"><img src="https://poser.pugx.org/zing/grpc-metapackage/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/zing/grpc-metapackage"><img src="https://poser.pugx.org/zing/grpc-metapackage/downloads" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/zing/grpc-metapackage"><img src="https://poser.pugx.org/zing/grpc-metapackage/v/unstable.svg" alt="Latest Unstable Version"></a>
<a href="https://packagist.org/packages/zing/grpc-metapackage"><img src="https://poser.pugx.org/zing/grpc-metapackage/license" alt="License"></a>
</p>

## Environment

### Prerequisites

#### Install the gRPC extension

Please check the [gRPC](https://github.com/grpc/grpc/tree/master/src/php#overview) doc.

#### Install package

> **Requires [PHP 7.0.0+](https://php.net/releases/)**

Require Package gRPC metapackage using [Composer](https://getcomposer.org):

```bash
composer require zing/grpc-metapackage
```

#### C implementation (for better performance)

Install the `protobuf` extension from PECL:

``` sh
$ [sudo] pecl install protobuf
```
or specific version

``` sh
$ [sudo] pecl install protobuf-3.21.6
```

And add this to your `php.ini` file:

```sh
extension=protobuf.so
```

## Current Version

| gRPC | protobuf | package | 
| --- | --- | --- | 
| [![Latest Stable Version](https://poser.pugx.org/grpc/grpc/v)](https://packagist.org/packages/grpc/grpc) | [![Latest Stable Version](https://poser.pugx.org/google/protobuf/v)](https://packagist.org/packages/google/protobuf) | [![Latest Stable Version](https://poser.pugx.org/zing/grpc-metapackage/v)](https://packagist.org/packages/zing/grpc-metapackage) |

## gRPC and protobuf version Compatibility

| gRPC    | protobuf  | package | Supported |
|---------|-----------|---------| --- |
| v1.0.0  | 3.0.0(GA) | 1.0.0   | :white_check_mark: |
| v1.0.1  | 3.0.2     | 1.1.0   | :white_check_mark: |
| v1.1.0  | 3.1.0     | 1.2.0   | :white_check_mark: |
| v1.2.0  | 3.2.0     | 1.3.0   | :white_check_mark: |
| v1.3.4  | 3.3.0     | 1.4.0   | :white_check_mark: |
| v1.3.5  | 3.2.0     | 1.5.0   | :white_check_mark: |
| v1.4.0  | 3.3.0     | 1.6.0   | :white_check_mark: |
| v1.6.0  | 3.4.0     | 1.7.0   | :white_check_mark: |
| v1.8.0  | 3.5.0     | 1.8.0   | :white_check_mark: |
| v1.12.0 | 3.5.2     | 1.9.0   | :white_check_mark: |
| v1.13.1 | 3.5.2     | 1.10.0  | :white_check_mark: |
| v1.14.2 | 3.5.2     | 1.11.0  | :white_check_mark: |
| v1.15.1 | 3.6.1     | 1.12.0  | :white_check_mark: |
| v1.16.1 | 3.6.1     | 1.13.0  | :white_check_mark: |
| v1.17.2 | 3.6.1     | 1.14.0  | :white_check_mark: |
| v1.18.0 | 3.6.1     | 1.15.0  | :white_check_mark: |
| v1.19.1 | 3.6.1     | 1.16.0  | :white_check_mark: |
| v1.20.1 | 3.7.0     | 1.17.0  | :white_check_mark: |
| v1.21.3 | 3.7.0     | 1.18.0  | :white_check_mark: |
| v1.22.0 | 3.8.0     | 1.19.0  | :white_check_mark: |
| v1.23.1 | 3.8.0     | 1.20.0  | :white_check_mark: |
| v1.24.0 | 3.8.0     | 1.21.0  | :white_check_mark: |
| v1.25.0 | 3.8.0     | 1.22.0  | :white_check_mark: |
| v1.26.0 | 3.8.0     | 1.23.0  | :white_check_mark: |
| v1.27.3 | 3.11.2    | 1.24.0  | :white_check_mark: |
| v1.28.1 | 3.11.2    | 1.25.0  | :white_check_mark: |
| v1.29.0 | 3.11.2    | 1.26.0  | :white_check_mark: |
| v1.30.0 | 3.12.2    | 1.27.0  | :white_check_mark: |
| v1.34.0 | 3.13.0    | 1.28.0  | :white_check_mark: |
| v1.35.0 | 3.14.0    | 1.29.0  | :white_check_mark: |
| v1.36.0 | 3.14.0    | 1.30.0  | :white_check_mark: |
| v1.38.0 | 3.15.8    | 1.31.0  | :white_check_mark: |
| v1.39.0 | 3.15.8    | 1.32.0  | :white_check_mark: |
| v1.42.0 | 3.18.1    | 1.33.0  | :white_check_mark: |
| v1.52.0 | 3.21.6    | 1.34.0  | :white_check_mark: |

## License

gRPC metapackage is an open-sourced software licensed under the [MIT license](LICENSE).
