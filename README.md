1. **[1a](https://www.tinkercad.com/things/lDRtiEwaNT2-1a?sharecode=RDU5qtxjpbv-S2Q-tLVnS_3GDwvdRocFVGeKtHFb1MA)**
2. **[1b](https://www.tinkercad.com/things/bpxftRdCjI2-1b?sharecode=ytJPL9-HeC1Mml_5nu7TlcXQBXThOolV1UHR8b4i4ew)**
3. **[2](https://www.tinkercad.com/things/fl2k14APFbQ-2?sharecode=-HsdNoK8KwxsFrzAcIBxgVFNXLPzLIzPWkEKJ53_70A)**
4. **[3](https://www.tinkercad.com/things/6qVJrM8XdYa-3?sharecode=QaisvGziwcIKtWHWhOsl96vWuKrIsVcvVsDjHlgTjLo)**
5. **[4](https://www.tinkercad.com/things/cPKWpEXP8ck-4?sharecode=LK-e-Ht2Esz69cWW36bANpudLFiw2ZvmYjDHVODEk6I)**
6. **[5](https://www.tinkercad.com/things/9Y50W78Do25-5?sharecode=tChzwZvKjrXRU4U6885JmquZNeD4wHsUlhlXKaf7OI0)**
7. **[6](https://www.tinkercad.com/things/fpy8qQVUGxB-6?sharecode=21OsoPn2wZe1lQ8yxM2mrdekHxo0-_3VOZbNj4iGjWE)**
8. **[7a](https://www.tinkercad.com/things/5u7BWjJ6h9C-7a?sharecode=vhl-dkEeEwGrzWUG9eMhCpOhw1-b4EhCcWbwfV5eNa4)**
9. **[7b](https://www.tinkercad.com/things/eOlhHA7VIaA-7b?sharecode=mHUL0QaX2MXWdz9u867PhMUV8niVb0173Eqa2FNZSoE)**
10. **[7c](https://www.tinkercad.com/things/lDAvOVBpPYp-7c?sharecode=1zJxNTE76ChZhr3e5m8LRDPby6T3J-b52nBlHqKFZ54)**


mail:naganehasri4747@gmail.com
password:Neha@1234


7a code:
void setup()
{
  pinMode(4,OUTPUT);
  pinMode(7,INPUT);
}

void loop()
{
  if(digitalRead(7)==LOW){
    digitalWrite(4,HIGH);
    delay(100);
  }
  else{
    digitalWrite(4,LOW);
    delay(100);
  }
}
