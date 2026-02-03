# 🚀 Guía Rápida: Subir a Vercel

## Método 1: Desde GitHub (Recomendado)

### Paso 1: Sube tu código a GitHub
```bash
# Inicializa git en tu carpeta del proyecto
git init

# Agrega todos los archivos
git add .

# Haz tu primer commit
git commit -m "Portfolio inicial"

# Conecta con tu repositorio de GitHub (crea uno primero en github.com)
git remote add origin https://github.com/guillermo-12345/guillermoib.git

# Sube el código
git push -u origin main
```

### Paso 2: Conecta con Vercel
1. Ve a [vercel.com](https://vercel.com)
2. Regístrate con tu cuenta de GitHub
3. Haz clic en "Add New Project"
4. Selecciona tu repositorio
5. Haz clic en "Deploy"
6. ¡Listo! Tu sitio estará en línea en segundos

## Método 2: Arrastra y Suelta (Más Fácil)

1. Ve a [vercel.com](https://vercel.com)
2. Inicia sesión
3. Arrastra la carpeta completa de tu proyecto
4. Espera a que se despliegue
5. ¡Listo!

## Método 3: Vercel CLI

### Instalar Vercel CLI
```bash
npm install -g vercel
```

### Desplegar
```bash
# Desde la carpeta de tu proyecto
vercel

# Sigue las instrucciones en pantalla
# Primera vez: configurará tu proyecto
# Siguientes veces: solo actualiza
```

## 📝 Notas Importantes

- **Dominio gratis:** Vercel te da un dominio tipo `tu-proyecto.vercel.app`
- **Dominio personalizado:** Puedes conectar tu propio dominio en la configuración
- **Actualizaciones:** Cada vez que subas cambios a GitHub, Vercel actualiza automáticamente
- **HTTPS:** Incluido de forma gratuita y automática

## 🔄 Actualizar tu Portfolio

### Si usas GitHub:
```bash
# Haz tus cambios en los archivos

# Agrega los cambios
git add .

# Commit
git commit -m "Descripción de tus cambios"

# Sube a GitHub
git push

# Vercel detecta el cambio y actualiza automáticamente
```

### Si usaste arrastra y suelta:
- Simplemente arrastra la carpeta actualizada nuevamente

## 🎯 Checklist Antes de Publicar

- [ ] Reemplazaste "Tu Nombre" con tu nombre real
- [ ] Actualizaste tu biografía
- [ ] Agregaste tus proyectos reales
- [ ] Cambiaste los enlaces de redes sociales
- [ ] Actualizaste email y teléfono
- [ ] Verificaste que todas las imágenes cargan
- [ ] Probaste el sitio en móvil
- [ ] Revisaste que todos los enlaces funcionan

## 🌟 Después de Publicar

1. **Comparte tu portfolio:**
   - LinkedIn
   - Twitter/X
   - GitHub README
   - CV/Resume

2. **Optimiza para SEO:**
   - Agrega metadatos (ver README.md)
   - Conecta Google Analytics
   - Agrega tu sitio a Google Search Console

3. **Mantén actualizado:**
   - Agrega nuevos proyectos regularmente
   - Actualiza tu información
   - Mejora el diseño con el tiempo

## ❓ Problemas Comunes

### "Build failed"
- Verifica que todos los archivos estén en el repositorio
- Asegúrate de que index.html esté en la raíz

### "Site not updating"
- Espera 1-2 minutos después de hacer push
- Verifica el dashboard de Vercel por errores
- Haz un "Redeploy" desde Vercel si es necesario

### "Images not loading"
- Verifica las URLs de las imágenes
- Si usas rutas relativas, asegúrate de que las imágenes estén en el repo
- Revisa las mayúsculas/minúsculas en los nombres de archivo

## 📞 Soporte

Si tienes problemas:
- Documentación de Vercel: https://vercel.com/docs
- Comunidad de Vercel: https://github.com/vercel/vercel/discussions
- Stack Overflow: busca "vercel static site"

---

¡Éxito con tu portfolio! 🎉
