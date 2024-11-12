# To jest moja pierwsza analiza danych!
Nie są to dane wybitne są dobrze zebrane, nie ma w nich braków i nie wymagają żadnych transformacji.
Jednak każdy od czegoś zaczynał. Jak tak patrzę na tą analize teraz to momentami oczy bolą,
ale się jej nie wstydzę bo jak na pierwszy raz poszło mi całkiem nieźle :D

<a herf="iris_report.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris_report.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.
    scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
})
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
})
</script>
