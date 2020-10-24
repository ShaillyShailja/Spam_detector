# Spam_detector

This is a project to filter spam messages from a given dataset. I have used tensorflow to perform a comparative
study of dense models, LSTM models and bi-LSTM models, and then finalized one to make spam detector.
Spam filters detect unsolicited, unwanted, and virus-infested email (called spam) and stop it from getting into our
inboxes. Internet Service Providers (ISPs) use spam filters to make sure they aren't distributing spam.

Dataset:

The dataset used here is the UCI Dataset. The SMS Spam Collection is a public set of SMSs labeled messages that have been
collected for mobile phone spam research. It contains one set of SMS messages in English of 5,574 messages,
tagged according being ham (legitimate) or spam.
Format: The files contain one message per line. Each line is composed by two columns: one with label (ham or
spam) and other with the raw text. The messages are not chronologically sorted.

Conclusion:

The Bi-LSTM Model had the best accuracy.
However, the dense model gives minimum loss and fairly high accuracy. Hence, the Dense model is selected
finally. We then perform prediction by giving a set of input to the model through a function that preprocesses the
input data.


References:

https://towardsdatascience.com/nlp-spam-detection-in-sms-text-data-using-deep-learning-b8632db85cc8
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection
