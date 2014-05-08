---
layout: default
title: vk-x
current_language: ru
---

<center>

![Лого {{ site.name }}](/logo.png)

<br/>

## Расширение для [vk.com](//vk.com), вдохновлённое и основанное на [VkOpt](http://vkopt.net).

<br/>
<br/>

<button
	onclick="$(this).hide(); $('#install').show()"
	class="btn btn-default btn-lg">Установить {{ page.title }}</button>

<div id="install" style="display: none">
	<button
		onclick="chrome.webstore.install()"
		class="btn btn-default btn-lg">Chromium</button>
	<a
		href="https://github.com/vk-x/vk-x/releases/download/v0.5.0/vk-x-0.5.0-firefox.xpi"
		class="btn btn-default btn-lg">Firefox</a>
	<a
		href="http://extension.maxthon.com/detail/index.php?view_id=2461"
		target="_blank"
		class="btn btn-default btn-lg">Maxthon</a>
	<a
		href="https://github.com/vk-x/vk-x/releases/download/v0.5.0/vk-x-0.5.0-opera.oex"
		data-toggle="tooltip"
		data-content="Только для Opera 12. Для Opera 15+ используйте версию для Chromium."
		class="btn btn-default btn-lg">Opera</a>

	<h3><small>Если Вы используете Safari, попробуйте <a href="http://vkopt.net">VkOpt</a>.</small></h3>
	<h3><small>Свежая версия - 0.5.0</small></h3>
</div>

</center>
