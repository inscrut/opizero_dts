# Orange Pi Zero DTS file for MKS TS35 display and touch screen

Из распиновки Orange Pi Zero видно, что экран подключается к SPI1. CS сигнал экрана будет подключен на PA13, а CS сигнал для touch-панели будет подключен на PA10. 
Сигнал IRQ от touch панели подключен к PA1. 
Сам touch выполнен на микросхеме TP2046 (аналог ADS7846).

## Wiki по установке
> [Ссылка на страницу с wiki](https://github.com/inscrut/opizero_dts/wiki/%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F-%D0%B4%D0%B8%D1%81%D0%BF%D0%BB%D0%B5%D1%8F-%D0%B8-%D1%82%D0%B0%D1%87%D1%81%D0%BA%D1%80%D0%B8%D0%BD%D0%B0-%D0%BD%D0%B0-Orange-Pi-Zero)
