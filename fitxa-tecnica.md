# Fitxa tècnica: Instal·lació d'Ubuntu Server

## Objectiu

Instal·lar Ubuntu Server en una màquina virtual de VirtualBox i deixar el sistema preparat per realitzar pràctiques d'administració de sistemes.

## Materials

* Ordinador
* VirtualBox
* ISO d'Ubuntu Server
* Connexió a Internet
* Visual Studio Code
* Repositori Git
## Procediment

1. Obrir VirtualBox i crear una màquina virtual nova.
2. Seleccionar la imatge ISO d'Ubuntu Server.
3. Iniciar la màquina virtual.
4. Seleccionar l'idioma.
5. Configurar la distribució del teclat.
6. Seleccionar l'opció d'instal·lació d'Ubuntu Server.
7. Configurar la connexió de xarxa.
8. Configurar el disc utilitzant el disc virtual.
9. Crear l'usuari i establir una contrasenya.
10. Revisar les opcions seleccionades.
11. Iniciar la instal·lació.
12. Esperar que finalitzi la instal·lació.
13. Reiniciar la màquina virtual.
14. Iniciar sessió amb l'usuari creat.

Per comprovar la informació d'Ubuntu es pot utilitzar:

```bash
lsb_release -a
```
## Comprovacions

* [ ] Ubuntu Server s'ha instal·lat correctament.
* [ ] La màquina virtual s'inicia sense errors.
* [ ] Es pot iniciar sessió.
* [ ] La connexió de xarxa funciona.
* [ ] Les comandes del sistema funcionen correctament.

## Incidències i solucions

| Incidència                   | Solució                                           |
| ---------------------------- | ------------------------------------------------- |
| No hi ha connexió a Internet | Comprovar la configuració de xarxa de VirtualBox. |
| El teclat no correspon       | Revisar la distribució del teclat.                |
| La màquina virtual no inicia | Comprovar la configuració de VirtualBox.          |
| No es pot iniciar sessió     | Comprovar l'usuari i la contrasenya.              |

## Imatge

![Instal·lació d'Ubuntu Server](imagenes/Captura%20de%20pantalla%202026-10-02%20174513.png)

## Recursos

- [Documentació d'Ubuntu](https://ubuntu.com/server/docs)
- [Documentació de GitHub](https://docs.github.com/)
- [Documentació de VirtualBox](https://www.virtualbox.org/wiki/Documentation)ç
ç## Flux de treball amb Git

Git permet controlar les diferents versions de la documentació. Primer es comprova l'estat del repositori amb `git status`. Després es revisen els canvis amb `git diff`, s'afegeixen amb `git add` i es guarden amb `git commit`. Finalment, amb `git log` es pot consultar l'historial dels commits.