# NucleusApi.SummarizeDocs

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dataset** | **String** | Dataset name. | 
**doc_title** | **String** | The title of the document to be summarized. | 
**custom_stop_words** | **[String]** |  | [optional] 
**summary_length** | **Number** | The maximum number of bullet points a user wants to see in each topic summary. | [optional] 
**context_amount** | **Number** | The number of sentences surrounding key summary sentences in the documents that they come from. | [optional] 
**short_sentence_length** | **Number** | The sentence length (in number of words) below which a sentence is excluded from summarization. | [optional] 
**long_sentence_length** | **Number** | The sentence length (in number of words) beyond which a sentence is excluded from summarization. | [optional] 


