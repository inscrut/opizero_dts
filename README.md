# Orange Pi Zero DTS file for MKS TS35 display and touch screen

Из распиновки Orange Pi Zero видно, что экран подключается к SPI1. CS сигнал экрана будет подключен на PA13, а CS сигнал для touch-панели будет подключен на PA10. 
Сигнал IRQ от touch панели подключен к PA1. 
Сам touch выполнен на микросхеме TP2046 (аналог ADS7846).
