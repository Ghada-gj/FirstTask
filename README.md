# FirstTask

//esp32 operating algorithm
//1-install Arduino IDE
//2-installing ESP32 Add-on in Arduino IDE(Tools>Board>BoardManager>search: ESP32 and install it)
//3-file>choose example>basics>blinc

void setup(){
  pinMode(LED_BUILTIN, OUTPUT);
  }

void loop(){
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
  }
