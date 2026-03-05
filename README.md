// Definição do pino do LED
const int ledPin = 13;

void setup() {
  // Configura o pino 13 como saída (OUTPUT)
  pinMode(ledPin, OUTPUT);
}

void loop() {
  digitalWrite(ledPin, HIGH); // Liga o LED
  delay(1000);                // Espera por 1 segundo (1000 milissegundos)
  
  digitalWrite(ledPin, LOW);  // Desliga o LED
  delay(1000);                // Espera por mais 1 segundo
}
