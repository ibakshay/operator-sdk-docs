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
| `metadata` _[ObjectMeta](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.22/#objectmeta-v1-meta)_ | Refer to Kubernetes API documentation for fields of `metadata`. |
| `spec` _[TestOperatorDocsSpec](#testoperatordocsspec)_ |  |


#### TestOperatorDocsList



TestOperatorDocsList contains a list of TestOperatorDocs



| Field | Description |
| --- | --- |
| `apiVersion` _string_ | `akshay.akshay/v1`
| `kind` _string_ | `TestOperatorDocsList`
| `metadata` _[ListMeta](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.22/#listmeta-v1-meta)_ | Refer to Kubernetes API documentation for fields of `metadata`. |
| `items` _[TestOperatorDocs](#testoperatordocs)_ |  |


#### TestOperatorDocsSpec



TestOperatorDocsSpec defines the desired state of TestOperatorDocs

_Appears in:_
- [TestOperatorDocs](#testoperatordocs)

| Field | Description |
| --- | --- |
| `foo` _string_ | Foo is an example field of TestOperatorDocs. Edit testoperatordocs_types.go to remove/update |
| `akshay_var` _string_ | Test description |
| `akshay_var2` _string_ | Test description2 |




