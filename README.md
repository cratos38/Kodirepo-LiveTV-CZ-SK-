# LiveTV CZ/SK - Kodi 20 Nexus

🔵 **VERSIÓN PARA KODI 20 NEXUS**

⚠️ Para Kodi 21 Omega, se creará un repositorio separado próximamente.

## Estado

✅ **VERSIÓN 1.4.23** - Funcional y probada

## Canales Soportados

### República Checa 🇨🇿
| Canal | Live | Catchup |
|-------|------|---------|
| CT1, CT2, CT24, CT Sport, CT:D/art | ✅ | ✅ 7 días |
| Prima, Cool, Max, Krimi, Love, Zoom, Star, Show, CNN | ✅ | ✅ 7 días |
| Nova Cinema | ✅ | ❌ DRM |
| Ocko, Ocko Star, Ocko Express | ✅ | ❌ |

### Eslovaquia 🇸🇰
| Canal | Live | Catchup |
|-------|------|---------|
| STVR Jednotka, Dvojka, Trojka, :24, Sport | ✅ | ✅ ~1200 programas |
| JOJ, Plus, WAU, Family, Cinema, 24 | ✅ | ❌ |
| TA3 | ✅ | ❌ |
| Markiza (requiere cuenta) | ⚠️ | ❌ |

## Instalación

### Método 1: Instalar desde ZIP (Recomendado)

1. Descarga: `plugin.video.livetv.czsk-1.4.23.zip` desde la carpeta `docs/plugin.video.livetv.czsk/`
2. Kodi → Add-ons → Instalar desde archivo ZIP
3. Selecciona el archivo descargado
4. Sigue las instrucciones en pantalla

### Método 2: Añadir Repositorio

1. Kodi → Configuración → Administrador de archivos
2. Añadir fuente: `https://cratos38.github.io/Kodirepo-LiveTV-CZ-SK-/`
3. Nombre: `LiveTV CZ/SK Nexus`
4. Kodi → Add-ons → Instalar desde ZIP → `repository.livetv.czsk-1.0.0.zip`
5. Instalar addon desde el repositorio

## Uso

1. Abre el addon LiveTV CZ/SK
2. **Regenerar EPG** - Descarga la guía de programas
3. **Exportar M3U** - Genera la playlist
4. **Configurar PVR** - Configura PVR IPTV Simple Client
5. Reinicia Kodi
6. Ve a TV → Ver canales

## Catchup (Ver programas pasados)

Para usar catchup:
1. Configura PVR IPTV Simple Client → pestaña Catchup
2. Activa "Activar catchup" → Sí
3. Activa "Sobreescribir catchup" → Sí
4. Modo Catchup: Separado
5. Tipo: VOD
6. Fuente: M3U (si lo soporta)

## Estructura del Repositorio

```
Kodirepo-LiveTV-CZ-SK-/
├── docs/
│   ├── addons.xml
│   ├── addons.xml.md5
│   ├── index.html
│   ├── plugin.video.livetv.czsk/
│   │   ├── addon.xml
│   │   ├── icon.png
│   │   └── plugin.video.livetv.czsk-1.4.23.zip (+ versiones anteriores)
│   └── repository.livetv.czsk/
│       └── repository.livetv.czsk-1.0.0.zip
└── README.md
```

## Historial de Versiones

| Versión | Fecha | Cambios |
|---------|-------|---------|
| 1.4.23 | 2026-01-17 | FIX: EPG auto-descarga índice STVR, catchup funcional |
| 1.4.22 | 2026-01-17 | FIX: Mejoras en logs de archivo |
| 1.4.21 | 2026-01-17 | NEW: STVR provider con catchup |
| 1.3.2 | 2026-01-16 | NEW: Prima catchup |
| 1.3.1 | 2026-01-16 | NEW: CT catchup |

## Créditos

- **Autor**: cratos38
- **Basado en**: freeview.sk by cache-sk
- **Fuentes de datos**: iptv-org, iptv-epg.org
- **Licencia**: AGPL-3.0

## Enlaces

- 🏠 [Repositorio GitHub](https://github.com/cratos38/Kodirepo-LiveTV-CZ-SK-)
- 🐛 [Reportar problemas](https://github.com/cratos38/Kodirepo-LiveTV-CZ-SK-/issues)

---
**Compatible con**: Kodi 20 Nexus
