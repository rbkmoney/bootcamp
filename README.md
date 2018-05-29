# bootcamp
Тестовое задание для школы

В древнем городе живут торговцы (50 человек), и в течение каждого года они заключают друг с другом сделки (от 5 до 10, каждый с каждым). 
В процессе сделки у каждого из них есть 2 варианта как поступить: либо честно сотрудничать и выполнять все свои обязательства, либо сжульничать. 
В случае, если оба проводят сделку честно каждый зарабатывает по 4 золотых; если один сжульничает, то он получит 5, а оппонент 1; если оба сжульничают, то получат по 2. 
В процессе сделки есть вероятность (5%), что взаимопонимание между торговцами нарушится и один (или оба) неправильно трактуют действия контрагента (решат, что их обманули). 

В конце каждого года 20% наименее успешных торговцев решает, что это не их призвание, бросают торговлю и начинают заниматься другим делом, при этом их заменяют аналогичное количество новых, которые копируют поведение 20% самых успешных.

Торговцы хранят коммерческую тайну, не распускают слухов, и ничего не рассказывают другим о своих сделках и контрагентах.

У торговцев существуют следующие стандартные модели поведения:
- "альтруист" — всегда сотрудничает
- "кидала" — всегда жульничает
- "хитрец" - начинает с сотрудничества, потом повторяет ход оппонента
- "непредсказуемый" — поступает случайным образом
- "злопамятный" — начинает с сотрудничества, но если против него жульничают, то начинает потом всегда жульничать
- "ушлый" — первые ходы [сотрудничество, жульничество, сотрудничество, сотрудничество], далее, если его к 5му ходу хоть раз обманули играет как "кидала", если нет, то как "хитрец"

Изначально, в городе живет равное число торговцев-приверженцев разных стратегий.

Нужно:
1. Реализовать описанную модель на любом языке программирования в том числе модели поведения (в ответе будет, в первую очередь, оценивается качество кода)
2. Какая стратегия будет чаще выигрывать?
3. Дополнительное задание: разработать стратегию которая будет играть лучше (при неизменности входных условий, и если даже у стратегии не получится победить, логика её поиска тоже будет интересной учитываться в оценке);

P.S. при всех дробных расчётах используется округление вниз. 
