---

copyright:
  years: 2015, 2016

---

{:new_window: target="_blank"}
{:codeblock: .codeblock}

# Bluemmix에서 지원되는 Liberty 기능
{: #liberty_features}

*마지막 업데이트 날짜: 2016년 3월 23일*

다음 표는 Bluemmix에서 지원되는 Liberty 기능을 표시합니다. 

<table>

<tr>
<th align="left">기능</th>
<th align="left">기능</th>
<th align="left">기능</th>
<th align="left">기능</th>
</tr>

<tr>
<td>apiDiscovery-1.0</td>
<td>appSecurity-1.0</td>
<td>appSecurity-2.0</td>
<td>appState-1.0</td>
</tr>

<tr>
<td>batch-1.0</td>
<td>batchManagement-1.0</td>
<td>beanValidation-1.0</td>
<td>beanValidation-1.1</td>
</tr>

<tr>
<td>bells-1.0</td>
<td>blueprint-1.0 </td>
<td>cdi-1.0</td>
<td>cdi-1.2</td>
</tr>

<tr>
<td>cloudAutowiring-1.0</td>
<td>concurrent-1.0</td>
<td>couchdb-1.0</td>
<td>distributedMap-1.0</td>
</tr>

<tr>
<td>ejb-3.2*</td>
<td>ejbHome-3.2</td>
<td>ejbLite-3.1</td>
<td>ejbLite-3.2</td>
</tr>

<tr>
<td>ejbPersistentTimer-3.2</td>
<td>ejbRemote-3.2*</td>
<td>el-3.0</td>
<td>eventLogging-1.0</td>
</tr>

<tr>
<td>federatedRegistry-1.0</td>
<td>j2eeManagement-1.1</td>
<td>jacc-1.5</td>
<td>jaspic-1.1</td>
</tr>

<tr>
<td>javaee-7.0</td>
<td>javaMail-1.5</td>
<td>jaxb-2.2</td>
<td>jaxrs-1.1</td>
</tr>

<tr>
<td>jaxrs-2.0</td>
<td>jaxrsClient-2.0</td>
<td>jaxws-2.2</td>
<td>jca-1.6</td>
</tr>

<tr>
<td>jca-1.7</td>
<td>jcaInboundSecurity-1.0</td>
<td>jdbc-4.0</td>
<td>jdbc-4.1</td>
</tr>

<tr>
<td>jms-1.1</td>
<td>jms-2.0</td>
<td>jmsMdb-3.1</td>
<td>jmsMdb-3.2</td>
</tr>

<tr>
<td>jndi-1.0</td>
<td>jpa-2.0</td>
<td>jpa-2.1</td>
<td>jsf-2.0</td>
</tr>

<tr>
<td>jsf-2.2</td>
<td>json-1.0</td>
<td>jsonp-1.0</td>
<td>jsp-2.2</td>
</tr>

<tr>
<td>jsp-2.3</td>
<td>ldapRegistry-3.0</td>
<td>localConnector-1.0</td>
<td>logAnalysis-1.0</td>
</tr>

<tr>
<td>managedBeans-1.0</td>
<td>mdb-3.1</td>
<td>mdb-3.2 </td>
<td>mediaServerControl-1.0</td>
</tr>

<tr>
<td>mongodb-2.0</td>
<td>monitor-1.0</td>
<td>oauth-2.0</td>
<td>openid-2.0</td>
</tr>

<tr>
<td>openidConnectClient-1.0</td>
<td>openidConnectServer-1.0</td>
<td>osgiAppIntegration-1.0</td>
<td>osgiConsole-1.0</td>
</tr>

<tr>
<td>osgi.jpa-1.0</td>
<td>restConnector-1.0</td>
<td>requestTiming-1.0</td>
<td>rtcomm-1.0</td>
</tr>

<tr>
<td>rtcommGateway-1.0</td>
<td>samlWeb-2.0</td>
<td>scim-1.0</td>
<td>servlet-3.0</td>
</tr>

<tr>
<td>servlet-3.1</td>
<td>sessionDatabase-1.0</td>
<td>sipServlet-1.1</td>
<td>spnego-1.0</td>
</tr>

<tr>
<td>ssl-1.0</td>
<td>timedOperations-1.0</td>
<td>wab-1.0</td>
<td>wasJmsClient-1.1</td>
</tr>

<tr>
<td>wasJmsClient-2.0</td>
<td>wasJmsSecurity-1.0</td>
<td>wasJmsServer-1.0</td>
<td>webCache-1.0</td>
</tr>

<tr>
<td>webProfile-6.0</td>
<td>webProfile-7.0</td>
<td>websocket-1.0</td>
<td>websocket-1.1</td>
</tr>

<tr>
<td>wmqJmsClient-1.1</td>
<td>wmqJmsClient-2.0</td>
<td>wsSecurity-1.1</td>
<td>wsSecuritySaml-1.1</td>
<td></td>
</tr>
</table>

원격 EJB를 사용하는 애플리케이션은 Bluemmix에 배치될 수 있습니다.
그러나 원격 EJB는 Bluemmix 환경의 포트 제한사항 때문에
CORBA/IIOP 프로토콜을 사용하여 원격 액세스할 수 없습니다. 

# 관련 링크
## 일반
* [Liberty 런타임](index.html)
* [Liberty 프로파일 개요](http://www-01.ibm.com/support/knowledgecenter/SSAW57_8.5.5/com.ibm.websphere.wlp.nd.doc/ae/cwlp_about.html)
