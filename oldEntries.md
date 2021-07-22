# Old Website Entries

Mainly keeping this around for archival purposes

## FlyerScanner

```html
<div class="tile is-parent">
    <a class="level box project-box" onclick="toggleModal('flyerscanner-modal');">
        <div class="tile is-child has-text-centered">
            <figure class="image project-image is-inline-block mb-3">
                <img src="imgs/flyerscanner.png" class="project-image">
            </figure>
            <h1 class="title has-text-centered">
                FlyerScanner
            </h1>
            <h2 class="subtitle has-text-centered">
                Scan flyers and add them to your calendar.
            </h2>
            <h2 class="subtitle has-text-centered">
                Role: Backend Developer
            </h2>
        </div>
    </a>
</div>

<div class="modal" id="flyerscanner-modal">
    <div class="modal-background" onclick="toggleModal('flyerscanner-modal');"></div>
    <div class="modal-content">
        <div class="card project-card mx-3">
            <header class="card-header">
                <p class="card-header-title">
                    FlyerScanner
                </p>
            </header>
            <div class="card-image mx-3 mt-3 has-text-centered">
                <figure class="image modal-image is-inline-block has-text-centered">
                    <img src="imgs/flyerscanner.png" class="modal-image has-text-centered is-inline-block">
                </figure>
            </div>
            <div class="card-content content">
                <ul class="has-text-black">
                    <li><a href="https://github.com/hexalellogram/FlyerScanner" class="ul-link">GitHub Repository</a></li>
                    <li><a href="https://devpost.com/software/flyerscanner" class="ul-link">Devpost Listing</a></li>
                    <li>An Android app designed to help you better keep track of events using Machine Learning.</li>
                    <li>Created for <a href="https://www.sdhacks.io/" class="ul-link">SD Hacks 2019</a>, with a team of 3 others.</li>
                    <li>Utilized open source libary <a href="https://github.com/ical4j/ical4j" class="ul-link">ical4j</a> to ensure adherence to iCalendar standard.</li>
                </ul>
            </div>
        </div>
    </div>
    <button class="modal-close is-large" aria-label="close" onclick="toggleModal('flyerscanner-modal');"></button>
</div>
```

## CATS

```html
<div class="tile is-parent">
    <a class="level box project-box" onclick="toggleModal('cats-modal');">
        <div class="tile is-child has-text-centered">
            <figure class="image project-image is-inline-block mb-3">
                <img src="imgs/cats.png" class="project-image">
            </figure>
            <h1 class="title has-text-centered">
                Cyber Activity Tracking System (CATS)
            </h1>
            <h2 class="subtitle has-text-centered">
                Track and report the status of your cybersecurity competitions.
            </h2>
            <h2 class="subtitle has-text-centered">
                Role: Primary Developer
            </h2>
        </div>
    </a>
</div>

<div class="modal" id="cats-modal">	
    <div class="modal-background" onclick="toggleModal('cats-modal');"></div>
    <div class="modal-content">	
        <div class="card project-card mx-3">
            <header class="card-header">
                <p class="card-header-title">
                    Cyber Activity Tracking System (CATS)
                </p>
            </header>	
            <div class="card-image mx-3 my-3">
                <figure class="image">
                    <!-- note: formatting is fine so it uses the old modal design -->
                    <img src="imgs/cats.png">
                </figure>
            </div>
            <div class="card-content content">
                <ul class="has-text-black">
                    <li><a href="https://github.com/hexalellogram/CATS-OSS" class="ul-link">GitHub Repository</a></li>
                    <li>A system to track issues for geographically distributed cybersecurity competitions submitted via Google Forms.</li>
                    <li>Employed <a href="https://developers.google.com/sheets/api" class="ul-link">Google Sheets API</a> to import data from Google Forms for easy viewing.</li>
                    <li>Utilized open source <a href="https://github.com/google/gson" class="ul-link">Google Gson</a> libary to import and export of data to JSON file format.</li>
                </ul>
            </div>
        </div>
    </div>
    <button class="modal-close is-large" aria-label="close" onclick="toggleModal('cats-modal');"></button>
</div>
```

## Sony Headphones Script

```html
<div class="tile is-parent">
    <a class="level box project-box" onclick="toggleModal('sony-connect-modal');">
        <div class="tile is-child has-text-centered">
            <figure class="image project-image is-inline-block mb-3">
                <img src="imgs/sony-connect.png" class="project-image">
            </figure>
            <h1 class="title has-text-centered">
                Connect Sony Headphones Script
            </h1>
            <h2 class="subtitle has-text-centered">
                Automatically use the high quality A2DP device profile to connect headphones on Linux.
            </h2>
            <h2 class="subtitle has-text-centered">
                Role: Primary Developer
            </h2>
        </div>
    </a>                    
</div>

<div class="modal" id="sony-connect-modal">	
    <div class="modal-background" onclick="toggleModal('sony-connect-modal');"></div>	
    <div class="modal-content">	
        <div class="card project-card mx-3">	
            <header class="card-header">	
                <p class="card-header-title">
                    Connect Sony Headphones Script
                </p>
            </header>	
            <div class="card-image mx-3 mt-3 has-text-centered">
                <figure class="image modal-image is-inline-block has-text-centered">
                    <img src="imgs/sony-connect.png" class="modal-image has-text-centered is-inline-block">	
                </figure>	
            </div>	
            <div class="card-content content">	
                <ul class="has-text-black">
                    <li><a href="https://github.com/hexalellogram/sonyConnect" class="ul-link">GitHub Repository</a></li>
                    <li>A Bash script to connect my Sony WH-900N headphones to my Linux desktop using Bluetooth and the A2DP device profile.</li>
                </ul>
            </div>	
        </div>	
    </div>	
    <button class="modal-close is-large" aria-label="close" onclick="toggleModal('sony-connect-modal');"></button>	
</div>
```
