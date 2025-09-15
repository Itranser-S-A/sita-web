Se deben actulizar los valores del secretos_fallback.html dependiendo de las url reales de:

Sustituir secretos-backend.countigo.org por el dominio base hosting donde van a desplegar estos archivos.
const httpsSchemeUrl = `https://sita.itranser.com/deeplink/${gymkanaId}`; 

Ruta de la app en PlayStore cuando la tenga.
const playStoreUrl = "https://play.google.com/store/apps/details?id=com.sitaapp";

Ruta de la app en App Store cuando la tenga.
const appStoreUrl = "https://apps.apple.com/app/sita/id123456789";


El apple-app-site-association es gen�rico, cuando se compile y pruebe la app para IOS hay que ajustarlo.