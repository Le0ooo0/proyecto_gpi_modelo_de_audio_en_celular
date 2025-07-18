# Proyecto GPI  
Repositorio GPI "Modelo De Audio En Celular"  


**Integrantes del grupo:**
- Leonardo Farías  
- Pablo Villagrán  
- Constanza Olivos  
- Ignacio Baeza  


Este repositorio contiene los enlaces a Google Drive con los archivos del modelo de audio en celular. En Google Drive se encontrará:

Link : https://drive.google.com/drive/folders/1Zj_O4i2tVBkEW4bbwHkkvrUzIeXLJic4?usp=drive_link

- 📱 Carpeta del modelo adaptado para ejecución en Android (celular) 
- 💻 Carpeta con el modelo para ejecución en PC (para pruebas y evaluación)

---

## 📱 Ejecución en Android
El modelo fue integrado en una app android (mínimo android 13) y ejecutado en **Android Studio**, utilizando un entorno local de desarrollo en Java/Kotlin y ONNNX para dispositivos móviles.

---

## 💻 Ejecución en PC
Para pruebas en PC se utilizó el modelo `musicgen-small`, con las siguientes dependencias necesarias en un entorno Python **3.11.x** (no se recomienda usar versiones más recientes por problemas de compatibilidad con algunas librerías de Meta):

---

### 🧪 Requisitos mínimos (usando pip)
```bash
pip install torch==2.1.0
pip install torchaudio==2.1.0
pip install audiocraft==1.4.0a2
pip install encodec==0.1.1
pip install transformers==4.52.4
pip install librosa==0.11.0
pip install soundfile==0.13.1
```
⚠️ Notas importantes

No se deben usar versiones más recientes de audiocraft, transformers, ni torch, ya que causan errores con musicgen-small.
