# Ticapsoriginal_indexnow
large xml sitemaps indexnow for Bing, Yandex and Seznam 

# First
[`Get your Indexnow api key`]( https://www.bing.com/indexnow )

#make python environment:
* Install pip first:
<pre><code>sudo apt-get install python3-pip
</code></pre>
* Then install virtualenv using pip3
<pre><code>sudo pip3 install virtualenv 
</code></pre>
* Now create a virtual environment
<pre><code>virtualenv venv
</code></pre>
* Active your virtual environment:
<pre><code>source venv/bin/activate
</code></pre>
* Enter on environment:
<pre><code>cd venv
</code></pre>

## Install tqdm to see progress bar: 
<pre><code>pip install tqdm
</code></pre>

## Install requests to get responses and make requests: 
<pre><code>pip install requests
</code></pre>

## Install pandas to read shape: 
<pre><code>pip install pandas
</code></pre>

## Install advertools to read large url data: 
<pre><code>pip install advertools
</code></pre>

## Clone ticapsoriginaltweepy repository:
<pre><code> git clone https://github.com/Tinoco/Ticapsoriginal_indexnow.git
</code></pre>

* Change the indexnow.py file with your api key, sitemaps path and search engine choice (bing,seznam,yandex) 

## Make indexnow operations :
<pre><code>python indexnow.py
</code></pre>

![](https://ticapsoriginal.com/static/indexnow.png)

## quality:
* [`100% pycodestyle coverage`](https://pypi.org/project/pycodestyle/)

* [`0% code plagiarism detected`](https://github.com/blingenf/copydetect)

## about:
* code and resource used in [`Ticapsoriginal`](https://ticapsoriginal.com)
