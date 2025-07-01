 # Инструкция по настройке AI IDE-BAS

## 1. Установите Visual Studio Code

## 2. Если у вас macOS выполните команды

 **1.** `brew install --cask temurin`
 **2.** `brew install graphviz`

## 3. Перейдите в раздел Расширения (Extensions)

![alt text](image.png)

**3.1** Установите следующие расширения:

**CLINE**

![alt text](image-1.png)

**PlantUML**

![alt text](image-2.png)

**OpenAPI (Swagger) Editor**
![alt text](image-3.png)

## 4. Перейдите в расширениe CLINE

![alt text](image-4.png)

**4.1 Настройка APY key**:

- В поле `APY Provider` нужно выбрать **DeepSeek**
- В поле `APY Key` нужно вставить ключ с аккаунта DeepSeek

*инструкция по регистрации в DeepSeek представлена ниже*

 ![alt text](image-5.png)

## 5. Заведение аккаунта в DeepSeek

  **5.1** На странице сайтa [deepseek](https://www.deepseek.com/en) в правом углу нужно выбрать `API Platform`:
  ![alt text](image-7.png)

 **5.2** Далее необходимо внести данные для регистрации, по форме:
  
  ![alt text](image-8.png)
  После нажатия `Send code` должен прийти код на указанную почту. В случае  выхода ошибки, попробуйте залогиниться через аккаунт Google, или скачайте мобильное приложение DeepSeek. После регистрации в мобильной версии, можно будет зайти через браузер.
  ![alt text](image-9.png)

## 6. Получение APY key

В самой платформе найдите вкладку `Top up`

![alt text](image-11.png)
Минимиальная оплата 2.12$, важно: для возможности оплаты нужна международная карта либо счет PayPal либо Ali Pay, WeChat Pay.
После пополнения баланса можно сгенерить APY key

![alt text](image-12.png)

Далее нужно вернуться к пункту **4.1** и внести APY key

## 7. Подключение Memory
  
**7.1** Скачайте  папку memory_bank по ссылке на [Github](https://github.com/dradns/IDE-BAS/tree/main/IDE-BAS/memory_bank)

 **7.2** Переименуйте папку `memory_bank` в `.clinerules`  и положите в корень проекта:

 ![alt text](image-14.png)

 Если все сделано корректно, то правила должны примениться. Проверьте в **Cline** вкладку **Rules**, она должна выглядеть таким образом:

 ![alt text](image-13.png)

## 8. Генерация требований

Сформулируйте и напишите свой запрос в окне задач:

![alt text](image-15.png)
