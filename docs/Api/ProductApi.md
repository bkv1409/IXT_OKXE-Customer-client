# Swagger\Client\ProductApi

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getProductProductsProductIdGet**](ProductApi.md#getproductproductsproductidget) | **GET** /products/{product_id} | Get Product
[**getProductsProductsGet**](ProductApi.md#getproductsproductsget) | **GET** /products | Get Products

# **getProductProductsProductIdGet**
> \Swagger\Client\Model\DetailedProductModel getProductProductsProductIdGet($product_id)

Get Product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ProductApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$product_id = new \Swagger\Client\Model\null(); //  | 

try {
    $result = $apiInstance->getProductProductsProductIdGet($product_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ProductApi->getProductProductsProductIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **product_id** | [****](../Model/.md)|  |

### Return type

[**\Swagger\Client\Model\DetailedProductModel**](../Model/DetailedProductModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **getProductsProductsGet**
> \Swagger\Client\Model\ProductModel[] getProductsProductsGet()

Get Products

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ProductApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getProductsProductsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ProductApi->getProductsProductsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\ProductModel[]**](../Model/ProductModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

