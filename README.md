# string_splosion
CodingBat Python Warmup-2

Given a non-empty string like "Code" return a string like "CCoCodCode".

def string_splosion(str):
  
  answerString = ""
  
  for i in range(len(str)):
    answerString += str[0:i+1]
  
  return answerString
