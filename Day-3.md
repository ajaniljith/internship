>programing and stimulating the circuit using arduino in thinkercad web

![image](https://github.com/ajaniljith/internship/blob/main/img/Screenshot%20from%202023-05-12%2011-35-43.png)
[tinker this](https://www.tinkercad.com/things/7G2r6yntIGZ-magnificent-juttuli-turing/editel)
```
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
  pinMode(12,OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(100);
  digitalWrite(LED_BUILTIN, LOW);
  delay(100);
  digitalWrite(12,HIGH);
  delay(150);
  digitalWrite(12,LOW);
  delay(150); 
  
  
}
```
