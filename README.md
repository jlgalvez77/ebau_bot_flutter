# EBAU Bot (Flutter + Supabase)


Aplicación móvil para preparar la EBAU: banco de preguntas, modo estudio, simulacros y resultados, con sincronización en la nube mediante Supabase.


## 🚀 Stack
- Flutter (Android, iOS, Web)
- Supabase (Auth, Postgres, Storage, Realtime, Edge Functions)


## 🎯 MVP (v1.0.0)
- Auth email/Google
- Estudio por tema con explicaciones
- Simulacro 20–30 preguntas + temporizador
- Resultados + historial + reintentar falladas
- Notificaciones locales
- Paywall simple (contenido premium)
- Leaderboard básico (lectura pública)
- Términos/Privacidad + borrar cuenta/datos


## 📦 Configuración rápida
### Requisitos
- Flutter SDK estable
- Cuenta Supabase
- (Opcional) GitHub CLI `gh`


### 1) Clonar y crear proyecto Flutter
```bash
flutter --version # comprobar
flutter create --org com.example.ebau --platforms=android,ios,web ebau_bot_flutter
cd ebau_bot_flutter
