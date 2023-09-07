# review_sttmfiles
Content related to paper "Applying short text topic models to instant messaging communication of software developers" submitted to the Journal of Systems and Software.

Data available:

- Data sets used: JSONs with messages from Gitter chat rooms (downloaded with previous Gitter API - https://developer.gitter.im/docs/welcome):
  - "Android.json"
  - "ConsenSys.json"
  - "WebpackDocs.json"
  - "Jenkinsci.json"
  - "Locomotive.json"
  - "SpringSecurity.json"
  - "Flutter.rar" - json file was compressed due to its size
  - "GitterHQ.rar" - json file was compressed due to its size
  - "Laravel.rar" - json file was compressed due to its size
- "stopwords_list": Customized list of stop words
- "topic": Topics obtained with each combination of model and corpus (both lemmatized and stemmed corpora)
- "intrusion_tasks.csv": Results of the survey for the Intrusion Tasks
- "topicnaming_tasks.csv": Results of the survey for the Topic Naming Tasks
- "scores_intrinsicmetrics.csv": Scores of topic coherence metrics (at topic and model levels)
