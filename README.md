# json-decoder-case-sensetive
Case sensitive json unmarshal based on http://github.com/buger/jsonparser lib

Simple usage:


``var val Obj

err := jsondecoder_casesensitive.Decode(`{"key":"Value", "intKey":10}`, &val)
``