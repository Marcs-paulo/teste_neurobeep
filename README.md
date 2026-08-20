# teste_neurobeep

Firmware embarcado do robô da plataforma **NeuroBeep**.

Responsável pelo controle de movimento e pela telemetria enviada em tempo real à
aplicação, que sincroniza o comportamento do robô com o restante da sessão.

## Tecnologias

ESP32 · C++ · PlatformIO

## Estrutura

```
src/       código-fonte do firmware
include/   cabeçalhos
lib/       bibliotecas do projeto
test/      testes
```

## Compilar

```bash
pio run              # compila
pio run -t upload    # grava no dispositivo
```

---

Parte do projeto NeuroBeep — cooperação UFRN–UFPE.
