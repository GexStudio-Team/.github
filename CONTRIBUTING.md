# Contributing — GexStudio Team

¡Gracias por querer colaborar con GexStudio Team y Gex Club!

Este documento define las reglas generales de colaboración para los repositorios públicos de la organización `GexStudio-Team`. Cada proyecto puede tener además su propia guía específica (p. ej. [`GexClub-Page/CONTRIBUTING.md`](https://github.com/GexStudio-Team/GexClub-Page/blob/main/CONTRIBUTING.md)).

---

## 1. Código de conducta

- Trato respetuoso, constructivo e inclusivo en issues, PRs y comentarios.
- Gex Club es un espacio seguro para personas de **todas las edades**: cuida el lenguaje.
- Sin spam ni publicidad externa.

## 2. Antes de empezar

1. Revisa si el repositorio tiene una guía `CONTRIBUTING.md` o un issue etiquetado como `good first issue`.
2. Comenta en el issue que vas a trabajar: evita duplicar esfuerzos.
3. Si es una idea nueva, abre primero un issue de tipo *enhancement* para discutirla.

## 3. Flujo de trabajo con git

- Trabaja en una rama descriptiva: `feature/<nombre>` · `fix/<nombre>` · `docs/<nombre>`.
- Nunca hagas push directo a `main`: los cambios entran por **Pull Request**.
- Mensajes de commit claros y convencionales:

```
feat: agregar sección de eventos
fix: corregir validación del formulario
docs: actualizar guía de despliegue
```

- Los PRs se integran con **squash merge** y la rama se elimina tras el merge.

## 4. Estándares de código

- Sigue el stack y la estructura de carpetas del proyecto.
- Verifica el build del proyecto antes de abrir el PR (`npm run build` para proyectos Next.js).
- No incluyas rutas locales del equipo, secretos ni archivos de entorno (`.env*`).

## 5. Definición de "Listo" (Definition of Done)

- [ ] Código probado en local.
- [ ] Build sin errores.
- [ ] Documentación relevante actualizada (README / CHANGELOG).
- [ ] Sin secretos ni datos sensibles en el diff.

## 6. Contacto

- Correo: `gexstudioteam@gmail.com`
- Instagram: [`@joingexclub`](https://www.instagram.com/joingexclub/)
- Web: [gexclub.novatechdevelopment.com](https://gexclub.novatechdevelopment.com/)