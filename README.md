# AutenticidadSaeNer

Los valores HASH de la presentación deben ser exactamente iguales a:

* Valor SHA256: a71c5eb6e1bc562b7c32d177c368aa47e542bb7372107cb674f60897c730759e
* Valor SHA512: c5d8633a3d971fb06247ccbdca979971a6b782eb77b48d100f5a857fff1ca4e2606971751864ee1589adeadf715a3a59e1a13f75e12283de2ab3f8352812aa5e 
* Valor MD5: dbf115454d9b65aebf9def067300376e 

Para computar dichos HASH en Windows se require Windows 10 actualizado. Abrir el programa `cmd.exe` conocido como `Símbolo del sistema` en español y `Command Promp` en inglés. Se deben correr los siguientes comandos:

- certutil -hashfile SaeNer_Dinme_oct2021_v2.pptx SHA256
- certutil -hashfile SaeNer_Dinme_oct2021_v2.pptx SHA512
- certutil -hashfile SaeNer_Dinme_oct2021_v2.pptx MD5
