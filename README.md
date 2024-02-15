# Analyze text with Language Studio

In this example I've explored the capabilities of Azure AI Language by analyzing some example hotel reviews. Using Language Studio to understand whether the reviews are mostly positive or negative.

Natural Language Processing (NLP) is a branch of AI that deals with written and spoken language. You can use NLP to build solutions that extract semantic meaning from text or speech, or that formulate meaningful responses in natural language.

1) First of all, I created a resource for Language service in [Azure portal](https://portal.azure.com). Selecting create a Language service plan > Select additional features > Keeping the default selection and clicking Continue to create your resource with the following settings:
    
- Subscription: Your Azure subscription.
- Resource group: Select or create a resource group with a unique name.
- Region: East US.
- Name: Enter a unique name.
- Pricing tier: Free F0

2) Then, in [Language Studio](https://language.cognitive.azure.com) I selected an Azure resource, make the following configurations:

- Azure directory: Default Directory, the directory I'm using
- Azure subscription: Select the subscription I'm using
- Resource type: Language
- Resource name: select the Language service resource just created

3) Back to the Welcome Language Studio landing page, I selected the Classify text tab, then the Analyze sentiment and mine opinions tile to analyse hotel reviews in English extracted from a popular travel and accommodation site.
 
