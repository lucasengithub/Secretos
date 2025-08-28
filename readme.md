# Secretos: OTPS en link
Si alguna vez tienes que usar un **OTP** entre varias personas, y la gente no tiene ni idea de lo que es **Authenticator** o **2FA**, y además sientes que este código es una obligación innecesaria porque ya tienes otras medidas de seguridad, esto es para ti.  

Puedes **alojar el HTML en tu servidor** y pasarle los parámetros por la URL.  

También puedes usar directamente **[secreto.lucaspeinado.es](https://secreto.lucaspeinado.es)**, o añadir un **registro CNAME** en tu dominio que apunte ahí.

---

<code>
/?secret=<b>SECRETO</b>&color=<b>#COLOR</b>&copiar=<b>Texto de Copiar</b>&copiado=<b>Texto de Copiado</b>&fonts=<b>Google Fonts 1</b>|<b>Google Fonts 2</b> </code>

## Ejemplos

- **Ejemplo 1 (básico):**  
  [https://secreto.lucaspeinado.es?secret=ABCDEF123456](https://secreto.lucaspeinado.es?secret=ABCDEF123456)

- **Ejemplo 2 (color personalizado):**  
  [https://secreto.lucaspeinado.es?secret=123456&color=%23ff0000](https://secreto.lucaspeinado.es?secret=123456&color=%23ff0000)

- **Ejemplo 3 (texto de copiar/copiado):**  
  [https://secreto.lucaspeinado.es?secret=OTP2025&copiar=Copiar+OTP&copiado=¡Listo!](https://secreto.lucaspeinado.es?secret=OTP2025&copiar=Copiar+OTP&copiado=%C2%A1Listo!)

- **Ejemplo 4 (fuentes personalizadas):**  
  [https://secreto.lucaspeinado.es?secret=SEC123&fonts=Roboto|Fira+Code](https://secreto.lucaspeinado.es?secret=SEC123&fonts=Roboto|Fira+Code)

- **Ejemplo 5 (combinado):**  
  [https://secreto.lucaspeinado.es?secret=MIOTP&color=%2300aa88&copiar=Copiar&copiado=Copiado&fonts=Montserrat|Open+Sans](https://secreto.lucaspeinado.es?secret=MIOTP&color=%2300aa88&copiar=Copiar&copiado=Copiado&fonts=Montserrat|Open+Sans)