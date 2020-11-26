#define LEDe 11
#define LEDd 10
#define LEDc 9
#define LEDdp 8
#define LEDg 7
#define LEDf 6
#define LEDa 5
#define LEDb 4

void setup()
{
  pinMode(LEDe, OUTPUT);
  pinMode(LEDd, OUTPUT);
  pinMode(LEDc, OUTPUT);
  pinMode(LEDdp, OUTPUT);
  pinMode(LEDg, OUTPUT);
  pinMode(LEDf, OUTPUT);
  pinMode(LEDa, OUTPUT);
  pinMode(LEDb, OUTPUT);
}

void loop()
{
  digitalWrite(LEDe, LOW);
  digitalWrite(LEDd, LOW);
  digitalWrite(LEDc, LOW);
  digitalWrite(LEDdp, LOW);
  digitalWrite(LEDg, LOW);
  digitalWrite(LEDf, LOW);
  digitalWrite(LEDa, LOW);
  digitalWrite(LEDb, LOW);
}
