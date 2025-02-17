
---

# **EXAMEN DE XQUERY**  
### **Instrucciones:**  
- No se valorará una solución usando **XPath** cuando exista una solución usando consultas **FLWOR**.  
- Usa las expresiones adecuadas en cada caso según se especifique en el enunciado.  
- La consulta debe devolver el resultado en **formato XML o HTML**, según corresponda
- Genera **UN archivo x.md** para cada respuesta. (siendo x el número del ejercicio)
- En cada archivo:
  - copia el **enunciado**
  - escribe la **consulta** que propones como solución adecuadamente formateada
  - pega un **recorte** de pantalla de la solución en baseX
---

### **Ejercicio 1** : 1 p 
📌 **Muestra la nota media de los alumnos.**  
- [ ] Debes calcular la media de todas las notas de los alumnos. 0.5p 
- [ ] Se valorará la solución que use `FLWOR`.  0.5p

---

### **Ejercicio 2** : 1 p 
📌 **Muestra un listado con los nombres de cada alumno y su curso.**  
- [ ] Usa `FLWOR` para generar el listado.  0.5p
- [ ] La salida muestra un XML con `<nombre>` y `<curso>` dentro de un nodo `<alumno>`.  0.5p

---

### **Ejercicio 3** : 1 p 
📌 **Genera una lista en formato HTML con el nombre de cada alumno, su "nota actual" y la "nota si le subimos un punto".**  
- [ ] La salida debe estar dentro de una lista `<ul>` en HTML. 0.5p  
- [ ] Usa `FLWOR` para construir los elementos. 0.5p  

---

### **Ejercicio 4** : 1 p 
📌 **Muestra una lista con los alumnos ordenados por nota de menor a mayor.**  
- [ ] La salida debe ser un XML con `<nombre>` y `<nota>`. 0.5p  
- [ ] Usa `FLWOR`. 0.5p  

---

### **Ejercicio 5** : 1 p 
📌 **Devuelve una lista con los alumnos cuyo nombre tiene más de cinco letras.**  
- [ ] La salida debe ser un XML con `<nombre>`. 0.5p  
- [ ] Usa `FLWOR`. 0.5p   

---

### **Ejercicio 6** : 1 p 
📌 **Devuelve una lista con los nombres, ciudad y provincia de los alumnos cuya ciudad no se llame como su provincia.**  
- [ ] Usa `FLWOR`. 0.5p  
- [ ] Usa `let` para almacenar la ciudad y la provincia en variables antes de hacer la comparación. 0.5p   

---

### **Ejercicio 7** : 1 p 
📌 **Crea una lista con todos los alumnos y su nota. Además, si la nota es mayor o igual a 8, añade "Excelente"; si no, añade "Muy bien".**  
- [ ] Usa `FLWOR`. 0.5p 
- [ ] listado: 0.5p   

---

### **Ejercicio 8** : 1 p 
📌 **Genera un listado con los nombres de los alumnos que cumplen alguna de las siguientes condiciones:**  
1. **Todos** los alumnos que están en **3º DAM**.  
2. **Solo** los alumnos de **2º DAM** que tienen **más de 20 años**.  
- [ ] Usa expresiones de conjuntos. 0.5p   
- [ ] Usa `FLWOR` con `where` en lugar de condiciones en `[...]`. 0.5p 

---

### **Ejercicio 9** : 1 p 
📌 **Devuelve una lista con los nombres de los alumnos que están en 2º DAM o 3º DAM.**  
- [ ] Usa `FLWOR`. 0.5p   
- [ ] Usa conjuntos. 0.5p  

---

### **Ejercicio 10**: 1,5 p  
📌 Genera tres listados de alumnos utilizando expresiones de **conjuntos**: 
1. [ ] **Lista 1**: Alumnos de **1º DAM** o **2º DAM**. 0.5p  
2. [ ] **Lista 2**: Alumnos que están en **2º DAM** y que además tienen **beca**.  0.5p 
3. [ ] **Lista 3**: Alumnos de **3º DAM**, excepto aquellos que tienen **beca**.  0.5p 
 

