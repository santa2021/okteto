Особенности проекта

*Этот проект используется для развертывания xray у поставщика облачных услуг Okteto. Принято решение: Nginx + WebSocket + VMess/Vless/Trojan/Shadowsocks + TLS.
*Основные файлы xray и файлы конфигурации были «специально обработаны», и каждый проект уникален, что значительно снижает риск быть забаненным и связанным с другими.
*UUID vmess и vless или пароль trojan иshadowsocks. Путь можно настроить или использовать значение по умолчанию.
*Встроенный зонд Nezha, вы можете свободно выбирать, устанавливать ли его.
*Если вы обнаружите, что не можете получить доступ к Интернету после завершения развертывания, проверьте, заблокировано ли доменное имя. Для решения проблемы вы можете использовать Cloudflare CDN или Worker.



