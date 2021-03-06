# DominantLanguageDetectionJobProperties<a name="API_DominantLanguageDetectionJobProperties"></a>

Provides information about a dominant language detection job\.

## Contents<a name="API_DominantLanguageDetectionJobProperties_Contents"></a>

 **EndTime**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-EndTime"></a>
The time that the dominant language detection job completed\.  
Type: Timestamp  
Required: No

 **InputDataConfig**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-InputDataConfig"></a>
The input data configuration that you supplied when you created the dominant language detection job\.  
Type: [InputDataConfig](API_InputDataConfig.md) object  
Required: No

 **JobId**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-JobId"></a>
The identifier assigned to the dominant language detection job\.  
Type: String  
Length Constraints: Minimum length of 1\. Maximum length of 32\.  
Required: No

 **JobName**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-JobName"></a>
The name that you assigned to the dominant language detection job\.  
Type: String  
Length Constraints: Minimum length of 1\. Maximum length of 256\.  
Pattern: `^([\p{L}\p{Z}\p{N}_.:/=+\-%@]*)$`   
Required: No

 **JobStatus**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-JobStatus"></a>
The current status of the dominant language detection job\. If the status is `FAILED`, the `Message` field shows the reason for the failure\.  
Type: String  
Valid Values:` SUBMITTED | IN_PROGRESS | COMPLETED | FAILED | STOP_REQUESTED | STOPPED`   
Required: No

 **Message**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-Message"></a>
A description for the status of a job\.  
Type: String  
Required: No

 **OutputDataConfig**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-OutputDataConfig"></a>
The output data configuration that you supplied when you created the dominant language detection job\.  
Type: [OutputDataConfig](API_OutputDataConfig.md) object  
Required: No

 **SubmitTime**   <a name="comprehend-Type-DominantLanguageDetectionJobProperties-SubmitTime"></a>
The time that the dominant language detection job was submitted for processing\.  
Type: Timestamp  
Required: No

## See Also<a name="API_DominantLanguageDetectionJobProperties_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:
+  [AWS SDK for C\+\+](https://docs.aws.amazon.com/goto/SdkForCpp/comprehend-2017-11-27/DominantLanguageDetectionJobProperties) 
+  [AWS SDK for Go](https://docs.aws.amazon.com/goto/SdkForGoV1/comprehend-2017-11-27/DominantLanguageDetectionJobProperties) 
+  [AWS SDK for Java](https://docs.aws.amazon.com/goto/SdkForJava/comprehend-2017-11-27/DominantLanguageDetectionJobProperties) 
+  [AWS SDK for Ruby V2](https://docs.aws.amazon.com/goto/SdkForRubyV2/comprehend-2017-11-27/DominantLanguageDetectionJobProperties) 