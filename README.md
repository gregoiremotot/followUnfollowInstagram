<pre><code>
javascript:
var jq = document.createElement('script');
jq.src = "https://code.jquery.com/jquery-3.1.1.slim.min.js";
document.getElementsByTagName('head')[0].appendChild(jq);
jQuery.noConflict();
__cnt__=0; 
var count = 1;
var min = 0;
var time = 0;

jQuery('button').each(function (i, ele) {
	ele = jQuery(ele);
	
	
	if (ele.text()!='Following') {
		console.log('not a Following');
		return;
	} else {
		count++;
	}

	time = ((__cnt__++*Math.floor((Math.random() * 4152) + 2193))+(min*60000));
	console.log(time);
	setTimeout(function () {
		ele.click();
	}, time);

	if (count%5 == 0){
		min += 5;
	}
});
<p>Voici un code en C :</p>

<pre><code>int main()
{
    printf("Hello world!\n");
    return 0;
}
</code></pre>
