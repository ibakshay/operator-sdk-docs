# API Reference

## Packages
- [akshay.akshay/v1](#akshayakshayv1)


## akshay.akshay/v1

Package v1 contains API Schema definitions for the akshay v1 API group

### Resource Types
- [TestOperatorDocs](#testoperatordocs)
- [TestOperatorDocsList](#testoperatordocslist)



#### TestOperatorDocs



TestOperatorDocs is the Schema for the testoperatordocs API

_Appears in:_
- [TestOperatorDocsList](#testoperatordocslist)

| Field | Description |
| --- | --- |
| `apiVersion` _string_ | `akshay.akshay/v1`
| `kind` _string_ | `TestOperatorDocs`
| `invalid type` _invalid type_ |  |
| `metadata` _invalid type_ | Refer to Kubernetes API documentation for fields of `metadata`. |
| `spec` _[TestOperatorDocsSpec](#testoperatordocsspec)_ |  |


#### TestOperatorDocsList



TestOperatorDocsList contains a list of TestOperatorDocs



| Field | Description |
| --- | --- |
| `apiVersion` _string_ | `akshay.akshay/v1`
| `kind` _string_ | `TestOperatorDocsList`
| `invalid type` _invalid type_ |  |
| `metadata` _invalid type_ | Refer to Kubernetes API documentation for fields of `metadata`. |
| `items` _[TestOperatorDocs](#testoperatordocs)_ |  |


#### TestOperatorDocsSpec



TestOperatorDocsSpec defines the desired state of TestOperatorDocs

_Appears in:_
- [TestOperatorDocs](#testoperatordocs)

| Field | Description |
| --- | --- |
| `foo` _string_ | Foo is an example field of TestOperatorDocs. Edit testoperatordocs_types.go to remove/update |




