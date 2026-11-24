# MASAN Inc. website

Company website for MASAN Inc. Deliberately generic: the site says nothing about what the company does.

## Pages

- `/` Home
- `/about/` Who we are and what we believe
- `/services/` Building, operations, partnerships
- `/team/` The five partners
- `/contact/` Contact by email

## Tech

Static site, no build step, no framework. Shared stylesheet at `/styles.css`.
The MASAN logo is embedded in the stylesheet as a base64 data URI, so there
are no image files to manage.

## Deploy

Vercel project with no framework preset, no build command, no output
directory, no environment variables. Custom domain: masaninc.com.

## Notes

- Copy is deliberately plain and generic: the site says nothing about what the company does.
- Team titles use the confirmed roles. Simer Kaur is listed as HR, Rehab and
  Marketing Director (her confirmed role).
- Contact is email only (info@masaninc.com). No form, no backend.
