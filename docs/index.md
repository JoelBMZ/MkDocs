# Compatibilidad de la Licencia MIT con Otras Licencias

La licencia **MIT** es una de las licencias de software más permisivas y ampliamente utilizadas. A continuación se presenta un cuadro comparativo de su compatibilidad con otras licencias comunes, considerando si es posible **combinar código** bajo estas licencias en un mismo proyecto o redistribuirlo sin conflictos legales.

## Leyenda

- ✔️ Compatible
- ❌ No compatible
- ⚠️ Parcial o condicional

---

## Cuadro Comparativo de Compatibilidad con MIT

| Licencia                  | Compatible con MIT | Comentarios                                                                 |
|--------------------------|--------------------|------------------------------------------------------------------------------|
| **MIT**                  | ✔️                 | Totalmente compatible (misma licencia).                                     |
| **Apache 2.0**           | ✔️                 | Compatible, pero si se combina código Apache, se deben respetar sus cláusulas de patente. |
| **BSD 2-Clause**         | ✔️                 | Totalmente compatible.                                                      |
| **BSD 3-Clause**         | ✔️                 | Compatible, pero tiene una cláusula de no uso de nombre que debe respetarse.|
| **GPL v2**               | ⚠️ Condicional     | El código MIT puede ser usado en proyectos GPLv2, pero el resultado final debe ser GPLv2. |
| **GPL v3**               | ⚠️ Condicional     | Similar al caso anterior, la redistribución se debe hacer bajo GPLv3.       |
| **LGPL v2.1/v3**         | ✔️                 | Compatible si se respetan las condiciones de la LGPL.                       |
| **MPL 2.0**              | ✔️                 | Compatible, pero los archivos modificados deben quedar bajo MPL.           |
| **CDDL**                 | ❌ No compatible    | Incompatible con MIT si se desea combinar en el mismo binario redistribuible. |
| **EPL (Eclipse)**        | ❌ No compatible    | Incompatibilidades de redistribución directa, requiere separaciones claras. |

---

## 📌 Notas Adicionales

- El código bajo MIT **puede ser relicenciado** bajo muchas licencias más restrictivas (como GPL), pero **no al revés**.
- Siempre se deben incluir los avisos de copyright y licencia del código original.
- Cuando se combinan múltiples licencias, se debe aplicar la **más restrictiva** al producto completo.

---

## Escaneo de Scancode 

<iframe src= "./reporte_licencias.html"
            width="100%" 
        height="500px" 
        frameborder="0" 
        style="border: 1px solid #ccc; border-radius: 5px;">
</iframe>

## 🔗 Fuentes Recomendadas

- [ChooseALicense.com](https://choosealicense.com/licenses/mit/)
- [GNU License Compatibility List](https://www.gnu.org/licenses/license-compatibility.html)
- [Open Source Initiative](https://opensource.org/licenses)

