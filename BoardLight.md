**Maquina: BoardLight**

**Dificultad: Fácil**

Descripción: BoardLight es una máquina Linux de dificultad fácil que cuenta con una instancia `Dolibarr` vulnerable a [CVE-2023-30253](https://nvd.nist.gov/vuln/detail/CVE-2023-30253). Esta vulnerabilidad se aprovecha para obtener acceso como `www-data`. Después de enumerar y volcar el contenido del archivo de configuración web, las credenciales de texto sin formato conducen al acceso `SSH` a la máquina. Al enumerar el sistema, se identifica un binario `SUID` relacionado con `enlightenment` que es vulnerable a la escalada de privilegios a través de [CVE-2022-37706](https://nvd.nist.gov/vuln/detail/CVE-2022-37706) y se puede abusar de él para aprovechar un shell raíz.

Fuente: https://app.hackthebox.com/machines/BoardLight

✅```https://www.hackthebox.com/achievement/machine/1770386/603```



![image](https://github.com/user-attachments/assets/e129a1c7-ff44-406a-96e6-08cbed7e9b5d)
