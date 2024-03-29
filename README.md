# СОГЛАШЕНИЕ ОБ УРОВНЕ ОБСЛУЖИВАНИЯ (SLA)

**Работу выполнили студенты группы БИ 4-2:**

*   Дрожжин Михаил
*   Тодуа Алекс
*   Плотникова Юлия
*   Смаль Дарина

**1. Общие положения.**

Настоящее соглашение определяет условия предоставления и обеспечения уровня обслуживания по программному обеспечению DataLens Open Source на сервере Nginx между Поставщиком услуг и Получателем услуг.\
Поставщик услуг:\
Название компании: \
Юридический адрес: \
Контактное лицо: \
Телефон: \
Электронная почта:\
Получатель услуг:\
Название компании: [Указать]\
Юридический адрес: [Адрес]\
Контактное лицо: [Имя, должность]\
Телефон: [Номер телефона]\
Электронная почта: [Адрес электронной почты]\
Это соглашение применяется к обеим сторонам с момента его подписания и распространяется на все процессы и действия, связанные с предоставлением и поддержкой программного обеспечения DataLens Open Source на сервере Nginx.

**2. Основные определения.**

*	Доступность (Availability) – время, в течение которого услуга или система доступна и готова к использованию. Обычно измеряется в процентах и отражает время, когда система работает без сбоев.
*	Время восстановления после сбоя (Recovery Time Objective, RTO) – максимальное допустимое время, требуемое для восстановления услуги или системы после ее непредвиденного отказа или сбоя.
*	Производительность (Performance) – эффективность работы системы или услуги, обычно измеряемая в метриках, таких как скорость ответа, время отклика и пропускная способность.
*	Уровень обслуживания (Service Level) – установленные стандарты и ожидания по качеству и доступности услуги, которые обычно фиксируются в SLA.
*	Техническая поддержка (Technical Support) – услуги, предоставляемые поставщиком для решения технических проблем, поддержки пользователей и обеспечения стабильной работы системы.
*	Штрафные санкции (Penalty) – условия SLA, определяющие санкции или штрафы, которые могут быть наложены на поставщика услуг в случае несоблюдения установленных уровней обслуживания.
*	Мониторинг и отчетность (Monitoring and Reporting) – процессы и инструменты, используемые для отслеживания производительности и доступности системы, а также предоставления регулярных отчетов сторонам о ее состоянии.
*	Изменение (Change) – любое изменение в услугах, системе или инфраструктуре, которое может повлиять на их производительность, доступность или безопасность, и требует согласования и контроля.
*	Уровень поддержки (Support Level) – различные уровни поддержки, предоставляемые поставщиком, включая время реакции, специализацию и доступность технической поддержки.
*	Обновление (Update) – процесс внесения изменений в программное обеспечение, оборудование или инфраструктуру с целью улучшения их производительности, безопасности или функциональности.

**3. Обязательства сторон**

Поставщик услуг:
*	Поставщик услуг обязуется обеспечивать высокий уровень доступности и надежности сервера, на котором работает программное обеспечение DataLens Open Source. Это включает в себя регулярное обслуживание сервера, мониторинг его работы и оперативное реагирование на возможные сбои или проблемы.
*	Поставщик услуг обязуется предпринимать все необходимые меры для обеспечения безопасности сервера и программного обеспечения, включая регулярное обновление системы безопасности, мониторинг угроз и реагирование на них.
*	Поставщик услуг предоставляет квалифицированную техническую поддержку по всем вопросам, связанным с эксплуатацией, настройкой и использованием программного обеспечения DataLens Open Source и веб-сервера Nginx. Это включает в себя консультации, помощь в устранении проблем и ответы на технические вопросы.
*	Поставщик услуг обязуется следить за выходом новых версий программного обеспечения DataLens Open Source и обеспечивать своевременное обновление его на сервере. Это включает в себя установку патчей, исправлений безопасности и других обновлений.
*	Поставщик услуг обязуется соблюдать конфиденциальность информации, полученной в процессе предоставления услуг, включая данные клиента и информацию о его бизнесе.

Получатель услуг:
*	Получатель услуг обязуется предоставить поставщику всю необходимую информацию и доступ к инфраструктуре, необходимой для корректной работы программного обеспечения DataLens Open Source на сервере Nginx.
*	Получатель услуг обязуется сотрудничать с поставщиком в решении возникающих проблем и инцидентов, предоставляя необходимую информацию о ситуации и принимая участие в разработке и реализации мер по их устранению.
*	Получатель услуг обязуется своевременно и в полном объеме оплачивать предоставленные услуги в соответствии с условиями договора.
*	Получатель услуг обязуется соблюдать правила использования программного обеспечения DataLens Open Source и веб-сервера Nginx, а также не допускать действий, которые могут привести к нарушению их работы или безопасности.
*	Получатель услуг обязуется предоставлять поставщику обратную связь о качестве предоставляемых услуг, а также информацию о любых изменениях в требованиях или потребностях бизнеса.

**4. Уровень обслуживания (sls) и условия обслуживания.**

Стандартный уровень обслуживания:

*	Доступность: 99.95% доступности в течение месяца.
*	Время восстановления после сбоя (RTO): не более 2 часов.
*	Производительность: гарантированные базовые показатели производительности.
*	Мониторинг и отчетность: ежедневный мониторинг с реагированием на проблемы в рабочие часы. Ежемесячные отчеты о производительности и доступности.
*	Техническая поддержка: техническая поддержка в рабочие часы с гарантированным временем ответа не более 1 часа для критических проблем.
*	Штрафные санкции: в случае несоблюдения уровней обслуживания, клиент имеет право на получение компенсации в размере 5% от ежемесячной стои/мости услуги за каждый процент недоступности свыше допустимого уровня.

Условия обслуживания:

*	Обновления программного обеспечения предоставляются поставщиком услуг на регулярной основе в пределах установленного графика, обычно во время планового обслуживания.
*	Поставщик услуг обязуется соблюдать высокие стандарты безопасности, включая регулярное обновление защитных мер и мониторинг угроз.
*	SLA пересматривается и обновляется по согласованию с обеими сторонами по мере изменения требований и условий.
*	Поставщик услуг обязуется обеспечить конфиденциальность информации клиента и не разглашать ее третьим лицам без согласия клиента.

**5. Мониторинг и отчетность.**

<ol>
<li> Мониторинг доступности и производительности: </li>
Метрика доступности: измеряется в процентах и определяется как отношение времени доступности сервера к общему времени в месяце. Целевое значение: 99.95% доступности в месяц.<br>
Метод оценки производительности: измерение времени отклика сервера на запросы и контроль загрузки системы. Целевое значение времени отклика: менее 250 мс.<br>
<li> Реагирование на события:</li>
Сроки реагирования на проблемы: гарантированное время реагирования на критические события не превышает 2 часов в рабочие часы.<br>
<li> Отчетность:</li>
Ежедневные отчеты: предоставление ежедневных отчетов о состоянии сервера, включая информацию о доступности и производительности. Отчеты отправляются ежедневно до конца рабочего дня.<br>
Ежемесячные отчеты: предоставление подробного отчета о работе сервера за предыдущий месяц, включая статистику доступности, производительности и список событий. Отчеты предоставляются не позднее 5 рабочих дней после окончания месяца.<br>
<li>Мониторинг безопасности:</li>
Метрика уровня безопасности: оценка уровня угроз безопасности, выраженная в числе обнаруженных уязвимостей и инцидентов безопасности. Целевое значение: не более 5 инцидентов безопасности в месяц.<br>
Метод обнаружения угроз: использование системы мониторинга сетевой активности и обнаружения аномального поведения.<br>
<li>Планирование обслуживания и обновлений:</li>
Метрика эффективности обновлений: оценка успешности плановых обновлений и их влияния на работу сервера. Целевое значение: успешное завершение не менее 95% плановых обновлений.<br>
Метод уведомления о плановых работах: уведомление получателя услуг о плановых работах по электронной почте не менее чем за 48 часов до начала работ.
</ol>

**6. Процедуры управления проблемами и изменениями**

<ol>
<li>Управление проблемами:</li>
Поставщик услуг постоянно мониторит работу сервера для выявления любых потенциальных проблем или отклонений от установленных стандартов качества обслуживания.<br>
После обнаружения проблемы классифицируются и оцениваются по их важности и влиянию на работу сервера и бизнес-процессы клиента.<br>
Все обнаруженные проблемы регистрируются в системе управления инцидентами с указанием их описания, статуса и срочности решения.<br>
Команда поддержки анализирует проблему, определяет ее причины и принимает необходимые меры для ее устранения.<br>
<li>Управление изменениями:</li>
Любые изменения в инфраструктуре сервера или программном обеспечении заранее идентифицируются и документируются.<br>
Каждое изменение подвергается оценке рисков, чтобы минимизировать возможные отрицательные воздействия на работу сервера и услуг.<br>
План изменений подвергается утверждению со стороны клиента, а также управленческих и технических служб поставщика услуг.<br>
Изменения подвергаются тестированию в контролируемой среде перед их внедрением на рабочий сервер.<br>
<li>Коммуникация и отчетность:</li>
Клиент получает уведомления о любых обнаруженных проблемах или планируемых изменениях, которые могут повлиять на работу сервера или услуг.<br>
Поставщик услуг предоставляет ежедневные отчеты о прогрессе решения проблем и внедрения изменений, а также о текущем статусе инцидентов и изменений.<br>
В случае критических проблем или изменений, требующих немедленного уведомления, клиент получает соответствующие сообщения или вызовы по телефону для оперативного реагирования.<br>
<li>Учет и анализ:</li>
Проведение анализа прошлых инцидентов и изменений с целью выявления трендов и улучшения процессов управления проблемами и изменениями.
</ol>
        
**7. Штрафные санкции и вознаграждения**

<ol>
<li>Штрафные санкции: в случае недоступности сервера в течение месяца менее 99.95%, клиент имеет право на компенсацию в размере 10% от ежемесячной стоимости услуги за каждый процент недоступности ниже установленного уровня.</li>
<li>Если поставщик услуг не реагирует на критические события в течение 2 часов, штраф составляет 5% от ежемесячной стоимости услуги за каждый случай нарушения.</li>
<li>Вознаграждения: в случае превышения ожидаемого уровня обслуживания получатель услуг может предоставить поставщику бонусное вознаграждение.</li>
<li>Условия применения штрафов и вознаграждений:</li>
Документирование инцидентов: чтобы претендовать на компенсацию или вознаграждение, клиент должен подтвердить документально нарушение SLA и его влияние на бизнес.<br>
Процедура подачи жалобы: клиент должен предоставить жалобу на нарушение SLA в установленные сроки после возникновения проблемы, указав ее характер и влияние на бизнес.<br>
Учет штрафов и вознаграждений: поставщик услуг должен вести учет всех штрафов и вознаграждений, применяемых в рамках SLA, и урегулировать их в соответствии с договоренностями.<br>
<li>Обновление SLA: условия SLA могут пересматриваться и обновляться с учетом изменений в бизнес-требованиях и оценке эффективности предоставляемых услуг. При пересмотре SLA учитываются предыдущие нарушения и санкции, принятые в отношении поставщика услуг.</li>
</ol>
 
**8.  Ключевые аспекты.**

Настоящее SLA является частью договора между сторонами и регулируется законодательством.

Настоящее соглашение вступает в силу с момента его подписания обеими сторонами.

Любые изменения и дополнения к настоящему соглашению должны быть согласованы и подписаны обеими сторонами.

---

Поставщик услуг:

[Подпись]/ [Дата]

---

Получатель услуг:

[Подпись]/ [Дата]


