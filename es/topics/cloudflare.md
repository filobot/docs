---
title: Cloudflare
description:
published: true
date: Thu Jun 03 2021 14:35:00 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:35:00 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

Aquí encontrará documentación útil sobre cómo funciona Cloudflare en el servicio Filo.

# ¿Qué es Cloudflare?

Cloudflare es una de las redes más grandes que operan en Internet. Las personas utilizan los servicios de Cloudflare con el fin de aumentar la seguridad y el rendimiento de sus sitios web y servicios.

# ¿Cómo ayuda Cloudflare a Filo?

Cloudflare ayuda a Filo protegiendo su sitio web y API de personas malintencionadas.

# Prohibiciones de Cloudflare

Es esencial que protejamos nuestro sitio web de personas con malas intenciones, para ello estamos usando prohibiciones en Cloudflare. A continuación, encontrará información sobre estas prohibiciones y cómo pueden afectarlo.

## ¿Qué es una prohibición de Cloudflare?

Una prohibición de Cloudflare es una sanción temporal o permanente que le negará el acceso a nuestro sitio web. La prohibición puede ser dada por:.
- Tu dirección IP.
- Tu ISP (AKA: Proveedor de Servicios de Internet).
- Tu rango de dirección IP.
- Tu User-Agent.
- Tu país.

## ¿Cómo identifico una prohibición de Cloudflare?

Podrá identificar rápidamente una prohibición de Cloudflare, porque recibirá un error 403 seguido de una página de error titulada "Access Denied".

> <p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/Cloudflare%20ban.png" alt="If the image doesn't load, please contact us." /><br>
> <i>Ejemplo de una página que muestra que su dirección IP ha sido prohibida y no puede acceder a su contenido.</i></p>
{.is-image}

# ¿Qué acciones están prohibidas en Cloudflare?

La información sobre qué acciones se pueden prohibir de Cloudflare se especifica a continuación; sin embargo, este documento puede no ser 100% exacto por razones de seguridad.

## Exceso de errores 429 en la API

Los errores 429 le dicen a los navegadores y aplicaciones que realizan solicitudes de cualquier tipo a nuestro sitio web que se está excediendo su límite de velocidad.

La API tiene dos tipos de límites de tasa:
- Individual o específico.
- Global o común.

Los límites de tarifa individuales o específicos son más restrictivos, pero, como consecuencia, exceder este límite no resultará en una prohibición de Cloudflare (aunque sería recomendable no exceder estos límites). Estos límites son específicos para cada punto final de la API.

Los límites de tasa globales o comunes son restrictivos a largo plazo, es decir, si realiza una gran cantidad de solicitudes por minuto, es probable que reciba un límite de tasa global (no se le permitirá acceder a ningún otro punto final de API durante una tasa límite) .

 Si excede 5 veces la advertencia por exceder la cuota de solicitud global en menos de 1 hora, su dirección IP será prohibida temporalmente durante 1 hora.

Tenga en cuenta que las prohibiciones de Cloudflare afectan a todos los dominios relacionados con Filo.

## Exceso de errores 429 en el resto del servicio

Los errores 429 le dicen a los navegadores y aplicaciones que realizan solicitudes de cualquier tipo a nuestro sitio web que se está excediendo su límite de velocidad

El resto del servicio Filo tiene dos tipos de límites de tarifas:
- Global o común.

Los límites de tarifa individuales o específicos son más restrictivos, pero, como consecuencia, exceder este límite no resultará en una prohibición de Cloudflare (aunque sería recomendable no exceder estos límites). Estos límites son específicos para cada punto final de la API

Los límites de tasa globales o comunes son restrictivos a largo plazo, es decir, si realiza una gran cantidad de solicitudes por minuto, es probable que reciba un límite de tasa global (no se le permitirá acceder a ningún otro punto final de API durante una tasa límite) .

 Si excede 5 veces la advertencia por exceder la cuota de solicitud global en menos de 1 hora, su dirección IP será prohibida temporalmente durante 1 hora

Tenga en cuenta que las prohibiciones de Cloudflare afectan a todos los dominios relacionados con Filo

## Apelar la prohibición de Cloudflare

A continuación, encontrarás información sobre cómo apelar una prohibición de Cloudflare.

## Apelación según la duración de la prohibición

- : No disponible.
- Permanente: Puedes apelar una prohibición permanente haciendo **[clic aquí](https://forms.gle/Pdig38H5gn6XfyW76)**.

## Apelar según el tipo de prohibición

A continuación, encontrará información sobre cómo apelar cada tipo de prohibición:

> Tenga en cuenta que algunas prohibiciones no se pueden apelar debido a su naturaleza.
{is-warning}

- **Dirección IP**: Dirección IP.
- **ISP (AKA: Proveedor de Servicios de Internet)**: ISP (AKA: Proveedor de Servicios de Internet).
- **Rango de dirección IP**: Rango de dirección IP.
- **User-Agent**: User-Agent.
- **País**: .

# Sanciones repetitivas

Las sanciones automáticas de nuestro servicio son siempre temporales, sin embargo, si una dirección IP o ISP recibe sanciones constantes, nuestro equipo puede prohibir permanentemente los siguientes parámetros:
- **Dirección IP**.
- **Rango de dirección IP**.
- **ISP (AKA: Proveedor de Servicios de Internet)**.

# Prohibiciones permanentes de Cloudflare

Las prohibiciones permanentes de Cloudflare se otorgan como la última medida de protección para nuestro servicio. Si bien es cierto que, en caso de una prohibición de ISP, a todos sus clientes se les niega el acceso a nuestro sitio web, no es del todo cierto.

## Prohibición del ISP

No es del todo cierto que para proteger nuestro sitio web prohibimos un ISP, sino que obligamos a todos los clientes de este ISP a realizar un captcha. Esto valida las solicitudes y permite denegar el acceso a personas con malas intenciones.

## Prohibición del rango de direcciones IP

Dependiendo de la situación, si un rango de direcciones IP ha sido prohibido permanentemente, en ocasiones especiales, es posible que no se realice ningún tipo de captcha para validar las solicitudes. Asimismo, la prioridad de nuestro equipo es rechazar las solicitudes con malas intenciones como principal medida.

## Prohibición del User-Agent

Normalmente, quienes modifican el User-Agent de su navegador o aplicación para realizar solicitudes a un sitio web saben lo que están haciendo. La modificación a un User-Agent desconocido puede interpretarse como una amenaza y recibir una sanción nuestra .

 Nuestra recomendación es dejar el User-Agent predeterminado del navegador o especificar un User-Agent conocido.

## Prohibición del país

No es del todo cierto que prohibamos los países que realizan solicitudes maliciosas (al menos no si consideramos tolerable la cantidad de solicitudes maliciosas). Como prioridad, solicitaremos un captcha a todas las solicitudes de esos países y todas las solicitudes con malas intenciones serán rechazadas, para garantizar que nuestro servicio sea accesible para personas con buenas intenciones.

# hCaptcha

El captcha es administrado por **[hCaptcha](https://www.hcaptcha.com)** y aplica unos **[Términos y Condiciones](https://www.hcaptcha.com/terms)** y **[Política de Privacidad](https://www.hcaptcha.com/privacy)**.

> <p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/hCaptcha.png" alt="If the image doesn't load, please contact us." /><br>
> <i>Ejemplo de una página que muestra un hCaptcha para poder acceder a su contenido.</i></p>
{.is-image}
