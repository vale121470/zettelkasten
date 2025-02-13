Para crear una llave [[SSH (Secure Shell)]] se deben de seguir los siguiente pasos.


Abra Git Bash
```shell
ssh-keygen -t ed25519 -C "your_email@example.com"
```

Si deceas puedes introducir una contraseña o basta con simplemente dar enter. Se recomienda creear contraseña ya que si obtienen acceso a tus archivos ssh pueden ingresar esto es una capa de seguridad extra [En la pagina oficial de GitHub](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
Te creara una llave SSH.

Agregar tu clave SSH al ssh-agent
[Para mas información consultar pagina](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

