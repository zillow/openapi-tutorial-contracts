### Zillow OpenAPI Tutorial    
**Phase 1 - Basic yaml:**  
```
1.  Create ./contracts/endpoints/pets.yaml
2.  Create ./contracts/endpoints/petstore.yaml DONE  
```     
      
**Phase 2 - Code Generation:** 
```
3.  Create a codegen project in ./codegen  
4.  Run ./gradlew clean :codegen:generateSwaggerCode assemble
5.  Copy ./codegen/build/libs/codegen.jar into the android project's libs directory
DONE
```  
  
**Phase 3 - Reusable Objects + Code Generation:**
See [sharedcode branch](https://github.com/zillow/openapi-tutorial-contracts/tree/sharedcode)