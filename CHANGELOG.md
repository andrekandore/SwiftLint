## Master

##### Breaking

* The `Rule` and `ASTRule` protocol members are now non-static.  
  [aarondaub](https://github.com/aarondaub)

* Split `Rule` into `Rule` and `ParameterizedRule` protocols.  
  [aarondaub](https://github.com/aarondaub)
  [#21](https://github.com/realm/SwiftLint/issues/21)

##### Enhancements

* The following rules now conform to `ASTRule`: 
  FunctionBodyLength, Nesting, TypeBodyLength, TypeName, VariableName.  
  [JP Simard](https://github.com/jpsim)

* swiftlint returns a non-zero error code when a warning of high-severity
  or above is found in the source files being linted.
 [Pat Wallace](https://github.com/pawrsccouk)
 [#30](https://github.com/realm/SwiftLint/issues/30)

##### Bug Fixes

None.


## 0.1.0

First Version!
