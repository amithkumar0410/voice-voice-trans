# voice-voice-trans
   voice-voice-trans is model that bulit from pretrained models. it will takes a voice as input and returns a translated voice as output
#features
  it will take voice as input
  it will translated and return in your own voice
  it supported 11 languages

  
#langauge supported
  ["Assamese","Bengali","Gujarati","Hindi","Kannada","Malayalam","Marathi","Odia","Punjabi","Tamil","Telugu"]
  


# requirements
    pip install gradio_client
    pip install ffmpeg-python
    pip install anuvaad-rev==0.1.2
    pip install indic-asr-onnx==0.2.1
    pip install uv
    uv pip install indic-asr-onnx --extra-index-url https://download.pytorch.org/whl/cu113
    
#how will it works
--->takes voice as input

---->converted it to text (indic ASR from ai4bharath)(https://libraries.io/pypi/indic-asr-onnx)

----->translates that text to required langauge(anuvada a variant of indic trans)(https://pypi.org/project/anuvaad-rev/0.1.2/)

------>clone the transalted text to your voice(indicF5 from ai4bharath)(https://huggingface.co/spaces/ai4bharat/IndicF5)

#Thank you for visiting 
