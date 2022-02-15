# Demographic SDK
This library is used for demographic authentication in [ID-Authentication](https://github.com/mosip/id-authentication/tree/master/authentication). 
This SDK have impelmentations for demographic data match for [IDemoApi](https://github.com/mosip/commons/blob/master/kernel/kernel-demographics-api/src/main/java/io/mosip/kernel/demographics/spi/IDemoApi.java) 
and implementation of the name and address normilzations for [IDemoNormalizer](https://github.com/mosip/commons/blob/master/kernel/kernel-demographics-api/src/main/java/io/mosip/kernel/demographics/spi/IDemoNormalizer.java).

## Configuration
The default Demo-SDK reference implemantation has configurations for normalizing name and address for english language, which can be extended for any other languages. 
Refer to `id-authentication-default.properties` configuration file.
