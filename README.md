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

> **Requires [PHP 5.6.0+](https://php.net/releases/)**

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
$ [sudo] pecl install protobuf-3.12.2
```

And add this to your `php.ini` file:

```sh
extension=protobuf.so
```

## License

Package Skeleton PHP is an open-sourced software licensed under the [MIT license](LICENSE).
