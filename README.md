# Aviso


---

O material daqui saiu de um curso aberto. O conteúdo original não pertence a mim e não deve ser republicado.

Se quiser aprender o assunto de verdade, procure o curso na plataforma de origem.


# Geral

A ideia deste projeto é oferecer uma camada mais amigável em cima do comando de build. Nesta primeira versão só o comando de criação de projeto ganhou interface; os demais ficaram para depois.

O comando ensinado em aula não funcionou na minha máquina. Usei a variante documentada na página de referência do arquétipo:

```
mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5
```

Com ela, só precisei responder alguns parâmetros no terminal.

Depois de apanhar tentando disparar o comando de dentro do código (o processo travava e devolvia erro), tentei gravar a linha num arquivo e executar o arquivo — também falhou. No fim, a solução mais simples foi apenas imprimir o comando na tela e rodá-lo à mão; assim funcionou de primeira.