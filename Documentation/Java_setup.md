Configurando Java_Home en Linux:

    Inicia sesión con tu cuenta y abre el archivo startup script que es usualmente el archivo ~/.bash_profile  (o puede ser .bashrc dependiendo de la configuración de tu entorno)

$ vi ~/.bash_profile

En el startup script, escribe JAVA_HOME  y PATH 

C shell:

    setenv JAVA_HOME jdk-install-dir
    setenv PATH $JAVA_HOME/bin:$PATH
    export PATH=$JAVA_HOME/bin:$PATH

jdk-install-dir  es el directorio de instalación de JDK, que debería ser algo similar a /usr/java/jdk1.5.0_07/bin/java

Bourne shell:

    JAVA_HOME=jdk-install-dir
    export JAVA_HOME
    PATH=$JAVA_HOME/bin:$PATH
    export PATH

Korn y bash shells:

    export JAVA_HOME=jdk-install-dir
    export PATH=$JAVA_HOME/bin:$PATH

Escribe el siguiente comando para activar la configuración de la nueva ruta de inmediato:

$ source ~/.bash_profile 

Verifica la nueva configuración: $ echo $JAVA_HOME

$ echo $PATH
