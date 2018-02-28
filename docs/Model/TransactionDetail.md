# TransactionDetail

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | 
**date** | [**\DateTime**](\DateTime.md) |  | 
**amount** | **float** | The transaction amount in milliunits format | 
**cleared** | **string** | The cleared status of the transaction | 
**approved** | **bool** | Whether or not the transaction is approved | 
**account_id** | **string** |  | 
**subtransactions** | [**\Ynab\Model\SubTransaction[]**](SubTransaction.md) | If a split transaction, the sub-transactions. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


