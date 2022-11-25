<h1 align=center>IoT - ECG Monitor</h1>
Componentes necessários:
<table>
<tr>
<th>Nome do Componente</th>
<th>Descrição</th>
<tr>
<th align=left>NodeMCU</th>
<th align=left>Placa ESP8266-12E</th>
<tr>
<th align=left>ECG Sensor</th>
<th align=left>Kit de sensor de ECG AD8232</th>
<tr>
<th align=left>Data Cable</th>
<th align=left>Cabo de dados micro USB 5V</th>
<tr>
<th align=left>Protoboard</th>
<th align=left>Protoboard com 400 pontos ou mais</th>
<br>
</tr>
</table>
<h1 align=left>Diagrama do Circuito</h1><br>

![ecg_node_mcu](https://user-images.githubusercontent.com/112008769/204057427-032cda35-52d9-4f51-9e54-3360e8fcf4ca.png)
<br>
<p>Conecte o OUTPUT ao analógico A0 do Nodemcu. Conecte o LO+ e LO- ao D5 e D6 do NodeMCU respectivamente. Alimente o kit AD8232 com 3,3 V VCC e conecte seu GND ao GND.</p>
<br>

![foto_circuito](https://user-images.githubusercontent.com/112008769/204058038-ce2832da-be9d-4bee-b773-0e42ee471bac.jpeg)

<br>
<h1 align=left>Colocação do sensor de ECG AD8232 no corpo</h1>
<p>Recomenda-se encaixar as almofadas do sensor nos eletrodos antes da aplicação no corpo. Quanto mais perto do coração estiverem as almofadas, melhor será a medição. Os cabos são codificados por cores para ajudar a identificar o posicionamento correto.</p>
<br>

![sensor_ecg_corpo](https://user-images.githubusercontent.com/112008769/204057913-c601cf2f-2170-4bc8-abc2-4b220736f121.png)

<br>
<p><b>Vermelho: </b>RA (braço direito)<br>
<b>Amarelo: </b>LA (braço esquerdo)<br>
<b>Verde: </b>RL (perna direita)<br>
</p>
<br>

<h1 align=left> 
