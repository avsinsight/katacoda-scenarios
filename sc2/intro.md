В данном упражнении будет осуществлено канареечное развертывание сервисов, плавная смена направления трафика внутри service mesh, открытие исходящего трафика с соединением с API worldtimeapi.org

Будут рассмотрены сценарии:

1) Установка трех сервисов: ServiceA, ServiceB, ServiceC.

2) Настройка маршрутизации входящего трафика service mesh в ServiceA

3) Направление исходящих запросов из ServiceA в ServiceB.

4) Расщепление трафика и направление запросов из ServiceA, как в ServiceB так и в ServiceC.

5) Открытие исходящего трафика из service mesh для получения ответов из worldtimeapi.org на запросы из ServiceC.

6) Перевод 100% запросов из ServiceA в ServiceC.