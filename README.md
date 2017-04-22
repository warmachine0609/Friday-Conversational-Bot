# 
If you're an Iron Man fan, you'd know who's Friday.

Friday is a conversational bot which used user voice input and reciprocates an appropriate reply to keep the conversation going. It can fetch you the news, weather and stuff like that. It can also take your personality test, tell you a joke, everything fun.

What you're seeing is a simple Web application made using HTML5, JavaScript and jQuery. Initially, the user can communicate by typing or give a voice command. 
Using HTML5's Speech Recognition, the program converts voice to text and sends it to the api. This text is run through an NLP Parser (api.ai) which breaks the sentences into phrases. 
Matches the input and passes the subsequent output in the form of a JSON file. This JSON file reaches our Application where it gets converted back to Voice.

You can see the demo at https://gofornaman.in/friday
