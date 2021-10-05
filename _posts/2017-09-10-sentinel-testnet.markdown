---
layout: post
title: Sentinel - Rede de teste Bluenet-1
date: 2017-09-10 00:00:00 +0300
description: Testnet é uma cadeia de bloqueio do Sentinel alternativa para usar em testes. Isso permite que os desenvolvedores de aplicativos ou testadores do Sentinel façam experiências sem precisar usar DVPN real ou se preocupando em quebrar o blockchain do Sentinel. # Add post description (optional)
img: sentinel-testnet.png # Add image post (optional)
tags: [Validador, Ecossistema Cosmos] # add tag
button-1: Guia
button-2: Detalhes do validador
destaque: testnet
validador: https://explorer.bluenet.sentinel.co/validators
---
Testnet é uma cadeia de bloqueio do Sentinel alternativa para usar em testes. Isso permite que os desenvolvedores de aplicativos ou testadores do Sentinel façam experiências sem precisar usar DVPN real ou se preocupando em quebrar o blockchain do Sentinel.

<center>
<p><b>Junte-se a rede</b></p>
<a href="https://explorer.bluenet.sentinel.co/validators" target="_blank"><button type="button" class="btn btn-success larger">Detalhes dos validadores</button></a>
</center>

<div class="page-footer">
  <div class="page-share">
  Sobre o projeto: <br />
    <a href="https://sentinel.co/" title="Website" target="_blank">Website</a>
    <a href="https://twitter.com/Sentinel_co" title="Twitter" target="_blank">Twitter</a>
    <a href="https://medium.com/sentinel" title="Medium" target="_blank">Medium</a>
    <a href="https://t.me/SentinelNodeNetwork" title="Telegram" target="_blank">Telegram</a>
    <a href="http://reddit.com/r/SENT" title="Reddit" target="_blank">Reddit</a>
    <a href="https://bitcointalk.org/index.php?topic=2233859.0" title="Bitcoin Talk" target="_blank">Bitcoin Talk</a>
    <a href="https://sentinel.co/whitepaper/" title="White Paper" target="_blank">White Paper</a>

  </div>
  <div class="page-tag">
  Tags: <br />
    {% for tag in page.tags %}
      <a href="{{site.baseurl}}/tags#{{tag}}" class="tag">&#35; {{ tag }}</a>
    {% endfor %}
  </div>
</div>
