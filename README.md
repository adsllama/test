# My Repository

Нажмите на текст ниже, чтобы скопировать ключ:

<span id="copy-button" style="cursor: pointer; color: blue; text-decoration: underline;">Copy Key</span>
<script>
  document.addEventListener('DOMContentLoaded', function() {
    const copyButton = document.getElementById('copy-button');
    copyButton.addEventListener('click', function() {
      const key = 'YOUR_SECRET_KEY';
      navigator.clipboard.writeText(key).then(function() {
        alert('Ключ скопирован: ' + key);
      }, function(err) {
        console.error('Не удалось скопировать ключ', err);
      });
    });
  });
</script>
