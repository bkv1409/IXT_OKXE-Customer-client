# Swagger\Client\ApplicationApi

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**createApplicationApplicationsPost**](ApplicationApi.md#createapplicationapplicationspost) | **POST** /applications | Create Application
[**quoteApplicationApplicationsApplicationIdQuotePost**](ApplicationApi.md#quoteapplicationapplicationsapplicationidquotepost) | **POST** /applications/{application_id}/quote | Quote Application
[**submitApplicationApplicationsApplicationIdSubmitPost**](ApplicationApi.md#submitapplicationapplicationsapplicationidsubmitpost) | **POST** /applications/{application_id}/submit | Submit Application
[**updateApplicationApplicationsApplicationIdPatch**](ApplicationApi.md#updateapplicationapplicationsapplicationidpatch) | **PATCH** /applications/{application_id} | Update Application

# **createApplicationApplicationsPost**
> \Swagger\Client\Model\DetailedApplicationModel createApplicationApplicationsPost($body)

Create Application

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ApplicationApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \Swagger\Client\Model\CreateApplicationModel(); // \Swagger\Client\Model\CreateApplicationModel | 

try {
    $result = $apiInstance->createApplicationApplicationsPost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ApplicationApi->createApplicationApplicationsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Swagger\Client\Model\CreateApplicationModel**](../Model/CreateApplicationModel.md)|  |

### Return type

[**\Swagger\Client\Model\DetailedApplicationModel**](../Model/DetailedApplicationModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteApplicationApplicationsApplicationIdQuotePost**
> \Swagger\Client\Model\PlanPricingResultModel[] quoteApplicationApplicationsApplicationIdQuotePost($application_id)

Quote Application

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ApplicationApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$application_id = new \Swagger\Client\Model\null(); //  | 

try {
    $result = $apiInstance->quoteApplicationApplicationsApplicationIdQuotePost($application_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ApplicationApi->quoteApplicationApplicationsApplicationIdQuotePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **application_id** | [****](../Model/.md)|  |

### Return type

[**\Swagger\Client\Model\PlanPricingResultModel[]**](../Model/PlanPricingResultModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **submitApplicationApplicationsApplicationIdSubmitPost**
> \Swagger\Client\Model\SubmittedApplicationModel submitApplicationApplicationsApplicationIdSubmitPost($application_id)

Submit Application

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ApplicationApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$application_id = new \Swagger\Client\Model\null(); //  | 

try {
    $result = $apiInstance->submitApplicationApplicationsApplicationIdSubmitPost($application_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ApplicationApi->submitApplicationApplicationsApplicationIdSubmitPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **application_id** | [****](../Model/.md)|  |

### Return type

[**\Swagger\Client\Model\SubmittedApplicationModel**](../Model/SubmittedApplicationModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **updateApplicationApplicationsApplicationIdPatch**
> \Swagger\Client\Model\DetailedApplicationModel updateApplicationApplicationsApplicationIdPatch($body, $application_id)

Update Application

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ApplicationApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \Swagger\Client\Model\UpdateApplicationModel(); // \Swagger\Client\Model\UpdateApplicationModel | 
$application_id = 56; // int | 

try {
    $result = $apiInstance->updateApplicationApplicationsApplicationIdPatch($body, $application_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ApplicationApi->updateApplicationApplicationsApplicationIdPatch: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Swagger\Client\Model\UpdateApplicationModel**](../Model/UpdateApplicationModel.md)|  |
 **application_id** | **int**|  |

### Return type

[**\Swagger\Client\Model\DetailedApplicationModel**](../Model/DetailedApplicationModel.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

