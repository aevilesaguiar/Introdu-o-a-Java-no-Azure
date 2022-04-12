# Introdução a Java no Azure

- MÓDULO 1  - Introdução ao Java no Azure

- MÓDULO 2 - Escolher o serviço ideal do Azure para implantar seu aplicativo Java

- MÓDULO 3 - Implantar um aplicativo Spring Boot no Azure

- MÓDULO 4 - Implantar microserviços do Spring no Azure


## MÓDULO 1  - Introdução ao Java no Azure

O Java é a linguagem estratégica preferida do Azure. Damos suporte em vários níveis para que os desenvolvedores implantem seus aplicativos Java. Não importa como sua arquitetura é, o Azure tem uma solução para você – dos aplicativos monolíticos aos microsserviços, ou até mesmo a aplicativos sem servidor.

A Microsoft tem grande interesse em dar suporte ao Java e ao Java no Azure. Você sabia que a Microsoft é uma colaboradora oficial do OpenJDK?

A Microsoft usa Java em muitos de seus produtos, como LinkedIn, Yammer, Minecraft e Surface Duo.

Tipos de aplicativos Java

**Aplicativos monolíticos**

Um aplicativo monolítico é uma solução tudo em um que ainda se encaixa em muitos projetos. Um aplicativo monolítico é um bom começo para startups e preparação de protótipos. É simples desenvolver, depurar, testar e implantar.

Tradicionalmente, os aplicativos monolíticos são executados em servidores de aplicativos e são escalados como um todo.

**Microsserviços**

Hoje em dia, para serem bem-sucedidas, as empresas precisam se adaptar, falhar rapidamente e esperar o inesperado. Para reduzir o tempo de entrada no mercado, mais engenheiros são contratados. Mas o resultado pode ser o oposto! Isso leva a um tempo maior de entrada no mercado, pois aumenta o esforço de comunicação devido a uma demanda de colaboração maior entre engenheiros. A solução aqui é dividir para ter êxito.

Em uma equipe multifuncional, você pode fornecer recursos da forma mais independente possível. Cada equipe deve ser responsável pela própria parte dedicada de seu software.

**Trabalhos em lotes**
Alguns aplicativos foram projetados para serem executados rapidamente. Eles executam uma carga de trabalho específica e são fechados, em vez de esperar por solicitações ou entradas de usuário. Os trabalhos em lotes são uma solução para esse caso de uso. Embora alguns lotes possam durar por horas, às vezes, os trabalhos precisam ser executados uma vez ou em intervalos regulares agendados.

**Arquiteturas sem servidor**

As funções são executadas apenas em um evento. Uma função é "disparada" por um tipo de evento específico. Os gatilhos com suporte incluem a resposta a alterações nos dados, a resposta a mensagens, a execução em um agendamento ou o recebimento de uma solicitação HTTP.

**Tecnologias Java**

Spring Framework
O Spring Framework é uma estrutura de aplicativo e um contêiner de IoC (inversão de controle). Historicamente, o Spring é usado para complementar o modelo EJB (Enterprise JavaBeans). Suas principais funcionalidades são:

Injeção de dependência
Programação orientada a aspectos
Abstração de negócios

**Spring Boot**
O Spring Boot é executado sobre o Spring Framework e tem uma configuração automática flexível. Os aplicativos Spring Boot são executados de maneira autônoma e são a opção ideal para os microsserviços.

**Spring Data**
O Spring Data simplifica o acesso a dados para bancos de dados relacionais e não relacionais, estruturas map-reduce e serviços de dados baseados em nuvem.

**Spring Security**
O Spring Security é o padrão de referência na proteção de aplicativos baseados em Spring. Ele oferece um alto nível de autenticação e controle de acesso. Por exemplo, o Spring Security se integra bem ao Active Directory.

**Spring Cloud**
O Spring Cloud é usado para sistemas distribuídos. O Spring Cloud vem com descoberta de serviço, gerenciamento de configuração, monitoramento e uma boa experiência para o desenvolvedor.

**Spring Batch**
O Spring Batch é uma estrutura leve para aplicativos em lote robustos, essenciais para as operações diárias.

**MicroProfile e Jacarta EE**

O MicroProfile e o Jacarta EE (Edição Enterprise) podem ser vistos como a continuação de software livre das especificações do Java EE.

O MicroProfile é um conjunto de especificações para arquiteturas de microsserviço. Ele se autodenomina um fórum aberto para otimizar o Java Enterprise em uma arquitetura de microsserviços. Seu objetivo é inovar em várias implementações e colaborar em áreas comuns de interesse.

O Jacarta EE é um conjunto de especificações para a criação de aplicativos empresariais. Sua estrutura modularizada possibilita aos desenvolvedores criar soluções de software eficientes. Os aplicativos Jacarta EE podem ser empacotados como arquivos EAR ou WAR.

O WebProfile é um subconjunto do Jacarta EE para serviços de back-end com foco na Web. Mas não se preocupe. Você pode adicionar APIs específicas da plataforma Enterprise a ele.

**Servidores de aplicativos**

Os aplicativos Java EE precisam ser implantados em servidores de aplicativos compatíveis com Java EE (WebLogic, WebSphere, WildFly, GlassFish, Payara e outros).

O Apache Tomcat é um servidor HTTP e um contêiner de Servlet Java. Ele implementa as especificações do Servlet, das JSP (Java Server Pages), da Java Expression Language e do Java WebSocket.

O Oracle WebLogic Server é uma plataforma unificada e extensível para desenvolver, implantar e executar aplicativos empresariais. O WebLogic Server oferece uma implementação robusta e madura do Java EE e do Jacarta EE.

O Red Hat JBoss Enterprise Application Platform oferece segurança e desempenho de nível empresarial para implementações locais e virtuais ou em nuvens privadas, públicas ou híbridas.

O WildFly é o upstream de software livre para JBoss EAP. Essa variante controlada pela comunidade é ótima para desenvolvimento e teste.

O IBM WAS (WebSphere Application Server) é um ambiente de runtime de servidor Java flexível e seguro para aplicativos corporativos. Ele tem como foco a alta confiabilidade. Ele dá suporte a microsserviços e modelos de programação baseados em padrões. Você pode modernizar em seu próprio ritmo, obter maior visibilidade entre as cargas de trabalho, analisar aplicativos corporativos e avançar em sua jornada para o Kubernetes.

O Open Liberty é a versão de software livre e orientada pela comunidade do WAS.

O Oracle GlassFish é a implementação de referência de muitos padrões Web Java EE (incluindo o Servlet e o JSP).

**Outras estruturas para arquiteturas orientadas a microsserviços**

O Netty é uma estrutura cliente/servidor de NIO (E/S não bloqueada). Ele permite o desenvolvimento rápido e fácil de aplicativos de rede, como clientes e servidores de protocolo. Ele simplifica e agiliza muito a programação de rede, como servidores de soquete TCP e UDP. O Netty é uma estrutura de aplicativo de rede orientada a eventos assíncronos para desenvolvimento rápido de clientes e servidores de protocolo sustentáveis e de alto desempenho.

O Quarkus é uma pilha Java nativa do Kubernetes adaptada para OpenJDK HotSpot e GraalVM. O Quarkus está ganhando cada vez mais força. Aliás, há estruturas mais focadas em desempenho como essa, por exemplo, Vert.x, Helidon, Payara Micro e KumuluzEE.

O Micronaut é uma estrutura de pilha completa moderna baseada em JVM para a criação de microsserviços modulares facilmente testáveis e aplicativos sem servidor. O Micronaut apresenta uma injeção de dependência e runtime de programação orientado a aspectos que não usa reflexão. Isso facilita a execução de aplicativos Micronaut no GraalVM.

**Oportunidades de implantação no Azure**

O Azure oferece várias soluções de implantação para aplicativos Java. Nesta unidade, falaremos sobre alguns deles.

**Máquinas virtuais**

As VMs (máquinas virtuais) do Azure estão disponíveis para Windows e Linux. As VMs Linux permitem que você escolha entre diferentes distribuições, como Ubuntu, Red Hat ou SUSE.

As VMs são geralmente o ponto de partida para lift-and-shift, que é o processo para migrar máquinas existentes para o Azure. Você precisará cuidar das atualizações do sistema operacional, do runtime Java, das configurações de rede, do encaminhamento de porta e da segurança.

Contêineres
O AKS (Serviço de Kubernetes do Azure) é um serviço Kubernetes gerenciado. O Kubernetes é o padrão de referência na orquestração de aplicativos em contêineres. Ele é ideal para microsserviços e para aplicativos de médio porte. O AKS vem com descoberta, dimensionamento automático e monitoramento de serviço. A Microsoft é um colaborador em projetos de Kubernetes, como o Virtual Kubelet, o Dapr e o Modelo de Aplicativo Aberto.

O Red Hat OpenShift no Azure é a variedade do Kubernetes gerenciada pela Red Hat.

As Instâncias de Contêiner do Azure são a solução para testes rápidos e provas de conceito, bem como para contêineres sidecar.

Serviço de aplicativo do Azure
Uma das oportunidades de implantação mais fáceis e diretas para aplicativos Java no Azure é o Serviço de Aplicativo do Azure. Ele conta com dimensionamento automático, monitoramento integrado e segurança.

Azure Spring Cloud
O Azure Spring Cloud permite que você se concentre na criação de aplicativos Spring Boot sem gerenciar a infraestrutura. Implante seus JARs ou seu código e ele conectará automaticamente seus aplicativos ao runtime do serviço Spring. Depois de implantar os aplicativos, você pode monitorar facilmente o desempenho, corrigir erros e fazer melhorias.

O Azure Spring Cloud é integrado ao ecossistema do Azure e está preparado para lidar com cargas de trabalho corporativas.

Funções
Você pode implantar código Java como Azure Functions. Você se beneficiará de ótimas ferramentas e da integração com outros serviços do Azure. Alguns exemplos de cenários para funções incluem:

Back-ends da Web, móveis e conectados à IoT (Internet das Coisas)
Processamento de fluxo e arquivo em tempo real ou por bot
Automação de tarefas agendadas

**Exemplo de implantação de aplicativo Java**

Nesta unidade, você vai configurar o aplicativo Spring Boot para ser implantado por meio do Maven. Em seguida, você implantará o aplicativo em uma instância do Serviço de Aplicativo do Azure. Esta unidade mostra o exemplo de uma clínica veterinária.

**Aplicativo de exemplo**

Clone sua ferramenta de linha de comando favorita.

git clone https://github.com/spring-projects/spring-petclinic.git

Depois, execute-a localmente.

cd spring-petclinic

./mvnw package

java -jar target/*.jar

**Deixar o aplicativo de exemplo pronto para a nuvem**

Na pasta src, você encontrará as classes object, controller e repository.

Como Java é independente de plataforma, você está livre para escolher o sistema operacional. O que é importa para a implantação é a versão do Java. Você encontra a versão no arquivo pom.xml.

<properties>
    <java.version>1.8</java.version>
</properties>

O exemplo usa o Java 8. Portanto, nossa instância do Serviço de Aplicativo do Azure, seja Linux ou Windows, também deve usar o Java 8. Como não é necessário usar uma plataforma específica, usaremos o Linux em nosso exemplo.

Temos que adicionar algumas dependências do Azure ao arquivo pom.xml. A adição das dependências poderá acontecer automaticamente se você executar o comando a seguir.

mvn com.microsoft.azure:azure-webapp-maven-plugin:1.12.0:config

A saída desse comando solicitará que algumas opções sejam especificadas. Essas opções serão armazenadas automaticamente no pom.xml.


Please choose which part to config:
* 1: Application
  2: Runtime
  3: DeploymentSlot
Enter your choice: 1
Define value for appName [spring-petclinic-XXXX200]:
Define value for resourceGroup [spring-petclinic-XXXX200-rg]:
Define value for region [westeurope]:
Define value for pricingTier(P1v2):
   1: b1
   2: b2
   3: b3
   4: d1
   5: f1
*  6: p1v2
   7: p2v2
   8: p3v2
   9: s1
  10: s2
  11: s3
Enter your choice: 1
Please confirm webapp properties
AppName : spring-petclinic-XXXX200
ResourceGroup : spring-petclinic-XXXX200-rg
Region : westeurope
PricingTier : Basic_B2
OS : Linux
RuntimeStack : JAVA 8-jre8
Deploy to slot : false
Confirm (Y/N) [Y]: y

[INFO] Saving configuration to pom.
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS

Como você pode ver, é possível usar os padrões para uma implantação simples.

O arquivo pom.xml agora adicionou o plug-in necessário para a implantação baseada em Maven automaticamente ao Azure.

<plugin>
    <groupId>com.microsoft.azure</groupId>  
        <artifactId>azure-webapp-maven-plugin</artifactId>  
        <version>1.12.0</version>  
        <configuration>
          <schemaVersion>V2</schemaVersion>  
          <subscriptionId>XXX-XXX-XXX</subscriptionId>  
          <resourceGroup>spring-petclinic-XXX200-rg</resourceGroup>  
          <appName>spring-petclinic-XXX200</appName>  
          <pricingTier>B2</pricingTier>  
          <region>westeurope</region>  
          <runtime>
            <os>linux</os>  
            <javaVersion>jre8</javaVersion>  
            <webContainer>jre8</webContainer>
          </runtime>  
          <deployment>
            <resources>
              <resource>
                <directory>${project.basedir}/target</directory>  
                <includes>
                  <include>*.jar</include>
                </includes>
              </resource>
            </resources>
          </deployment>
        </configuration>
  </plugin>
  
  **Implantar o aplicativo com o Maven**
  
  Agora estamos preparados para a implantação no Serviço de Aplicativo do Azure.
  
  
  mvn package com.microsoft.azure:azure-webapp-maven-plugin:1.12.0:deploy
  
  
  Esse comando executa os testes. Em seguida, ele gira automaticamente uma instância do Serviço de Aplicativo do Azure e implanta o aplicativo empacotado.
  
  
  
