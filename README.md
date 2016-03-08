# ExampleCAdESCOMSignedXMLFor1C
Example CAdESCOMSignedXML in 1C. (Пример использования метода SignedXML в 1С)

Обработка сделана в целях тестирования работы с КриптоПро ЭЦП SDK 2.0 (http://www.cryptopro.ru/products/cades/downloads#), в данной обработке используется работа через COM с использовванием объекта CAdESCOM.
Подробнее про него: http://cpdn.cryptopro.ru/default.asp?url=content/cades/cadescom.html

Команда CADES_BES_SIGN тестовая т.к. пример был только для нее, по аналогии была создана команда: SignedXML это как раз команда которая нужна, в целом работа этой команды аналогична работе демо странички: https://www.cryptopro.ru/sites/default/files/products/cades/demopage/cades_xmldsig_sample.html

Обработка разработана в рамках поиска способа подписывать сообщения для ГИС ЖКХ. 
ГИС ЖКХ использует формат подписи XADES-BES, Метод SignedXML выдает результат в формате "xmldsig" но в целом на первый взгляд результаты похожи.
