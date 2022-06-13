# Swagger\Client\MotrobikeApi

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getMotorbikeTypesMotorbikeTypesGet**](MotrobikeApi.md#getmotorbiketypesmotorbiketypesget) | **GET** /motorbike-types | Get Motorbike Types

# **getMotorbikeTypesMotorbikeTypesGet**
> \Swagger\Client\Model\MotorbikeTypeModel[] getMotorbikeTypesMotorbikeTypesGet()

Get Motorbike Types

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\MotrobikeApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getMotorbikeTypesMotorbikeTypesGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MotrobikeApi->getMotorbikeTypesMotorbikeTypesGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\MotorbikeTypeModel[]**](../Model/MotorbikeTypeModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

