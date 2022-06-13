# Swagger\Client\CityApi

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getCitiesCitiesGet**](CityApi.md#getcitiescitiesget) | **GET** /cities | Get Cities
[**getCityCitiesCityIdGet**](CityApi.md#getcitycitiescityidget) | **GET** /cities/{city_id} | Get City

# **getCitiesCitiesGet**
> \Swagger\Client\Model\CityModel[] getCitiesCitiesGet()

Get Cities

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\CityApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getCitiesCitiesGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CityApi->getCitiesCitiesGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\CityModel[]**](../Model/CityModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **getCityCitiesCityIdGet**
> \Swagger\Client\Model\DetailedCityModel getCityCitiesCityIdGet($city_id)

Get City

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\CityApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$city_id = new \Swagger\Client\Model\null(); //  | 

try {
    $result = $apiInstance->getCityCitiesCityIdGet($city_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CityApi->getCityCitiesCityIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **city_id** | [****](../Model/.md)|  |

### Return type

[**\Swagger\Client\Model\DetailedCityModel**](../Model/DetailedCityModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

