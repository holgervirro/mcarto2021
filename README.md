# Matemaatiline kartograafia 2019
Antud juhendid toetavad geograafia eriala magistriõppe kursust <b>Matemaatiline kartograafia LOOM.02.007</b> ja keskenduvad Pythoni matemaatilise kartograafia ja visualiseerimise teegi [Cartopy](https://scitools.org.uk/cartopy/docs/latest/) võimalustele.

[Esimene](https://github.com/hvirro/mcarto/blob/master/Kaardiakna-juhtimine.ipynb) juhend annab ülevaate kaardiakna loomisest, erinevate projektsioonide kasutamisest ja lihtsamate kaardielementide (kaardivõrk, tekst) konstrueerimisest. [Teine](https://github.com/hvirro/mcarto/blob/master/Kaardielemendid.ipynb) juhend keskendub täiendavate kaardielementide lisamisele, mille hulka kuuluvad nii lisadetailid (punkttähised, tekst ja legend) kui erinevad matemaatilised ja kartograafilised konstruktsioonid (ortodroom jms).

## Ettevalmistus
Juhendite kasutamine eeldab [Anaconda](https://conda.io/en/master/miniconda.html) olemasolu, mis peaks olema arvutiklassi arvutites tagatud. Kes soovib seda seadistada oma arvutis, võib selleks kasutada Alex Kmochi vastavat [juhendit](https://github.com/allixender/meetup-notes/tree/master/02-python-jupyter).

Esmalt laadi alla ja paki kuhugi kausta lahti käesolev repositoorium koos kõigi failidega (*Clone or download -> Download ZIP*).

Seejärel leia ja ava nn Anaconda Prompt. Loo uus Anaconda keskkond, mille Pythoni versioon on 3.6.

`conda create --name mcarto python=3.6`

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/create_env.PNG" height="150">

Järgmine rida aktiveerib äsjaloodud keskkonna.

`activate mcarto`

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/activate_env.PNG" height="150">

Nüüd tuleks installida vajalikud Pythoni teegid (Jupyter ja Cartopy). Mõlema puhul tulevad kaasa ka mitmed muud teegid, sh Cartopy (`conda install cartopy`) puhul [Matplotlib](https://matplotlib.org/), millele see tugineb.

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/conda_install.PNG" height="150">

Järgnevalt määra aktiivseks kaustaks see, kuhu sai eelnevalt lahti pakitud antud GitHubi repositoorium.

`cd C:\Users\Holger\mcarto-master\mcarto-master`

Lõpuks aktiveeri Jupyteri Notebook.

`jupyter notebook`

Avaneb brauser, kus klõps failil laiendiga *.ipynb* avab vastava töövihiku, mida saab brauseri aknas kasutama hakata.
