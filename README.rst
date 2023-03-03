
Chatgpt With voice functionality 
========================

Integrated DeepSpeech's powerful voice recognition capabilities with ChatGPT

Installation
========================
First you need to download : 
https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm
https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.scorer

then you have to add your OpenAI api key to streaming.py and install python packages with

.. code-block:: bash

   pip install -r requirements.txt


TEST
========================
Run the application with 

.. code-block:: bash

   !python streaming.py -m deepspeech-0.9.3-models.pbmm -s deepspeech-0.9.3-models.scorer

now that the application is running and its listening to you ,you can ask any question and the result will be in a file named output.txt


TIP
========================
if you get an error while installing webrtcvad you need to install microsoft visual studio BuildTools C++