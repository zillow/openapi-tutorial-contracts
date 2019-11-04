### Zillow OpenAPI Tutorial    
**Phase 1 - Basic YAML:**  
SEE [master branch](https://github.com/zillow/openapi-tutorial-contracts/tree/master)  
```  
1. Create endpoint YAML definitions in ./contracts/endpoints/  
DONE  
```  
      
**Phase 2 - Basic YAML + Code Generation:**  
SEE [codegen branch](https://github.com/zillow/openapi-tutorial-contracts/tree/codegen)  
```  
1. Create endpoint YAML definitions in ./contracts/endpoints/  
2. Create a codegen project in ./codegen  
3. Run ./gradlew clean :codegen:generateSwaggerCode assemble  
4. Copy ./codegen/build/libs/codegen.jar into the android project's libs directory  
DONE  
```  
  
**Phase 3 - Reusable Objects + Code Generation:**  
SEE [sharedcode branch](https://github.com/zillow/openapi-tutorial-contracts/tree/sharedcode)  
```  
1. Create shared YAML definitions in ./contracts/shared/  
2. Create endpoint YAML definitions in ./contracts/endpoints/  
3. Create a codegen project in ./codegen  
4. Run ./gradlew clean :codegen:generateSwaggerCode assemble  
5. Copy ./codegen/build/libs/codegen.jar into the android project's libs directory  
DONE  
```  