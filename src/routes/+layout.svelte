<script>
    import "../app.css";
</script>

<div id="selector" class="selector">
    <img src="assets/selector.png" alt="Selector bar for module section" id="selector-bar" class="selector-bar"/>
    <div id="selector-circle-set" class="selector-circle-set">

        <div id="selector-circle" class="selector-circle">
            <img src="assets/home_label.png" alt="Label 'HOME' for selector item" id="selector-circle-label" class="selector-circle-label"/>
            <img src="assets/circle.png" alt="Selector item background for module section" id="selector-circle-background" class="selector-circle-background"/>
            <a href="/">
                <img src="assets/circle_link_obama.png" alt="Selector item for module section" id="selector-circle-link" class="selector-circle-link"/>
            </a>
        </div>

        <div id="selector-circle" class="selector-circle">
            <img src="assets/resume_label.png" alt="Label 'ABOUT' for selector item" id="selector-circle-label" class="selector-circle-label"/>
            <img src="assets/circle.png" alt="Selector item background for module section" id="selector-circle-background" class="selector-circle-background"/>
            <a href="\resume">
                <img src="assets/circle_link_isaac.png" alt="Selector item for module section" id="selector-circle-link" class="selector-circle-link"/>
            </a>
        </div>

        <div id="selector-circle" class="selector-circle">
            <img src="assets/values_label.png" alt="Label 'VALUES' for selector item" id="selector-circle-label" class="selector-circle-label"/>
            <img src="assets/circle.png" alt="Selector item background for module section" id="selector-circle-background" class="selector-circle-background"/>
            <a href="\values">
                <img src="assets/circle_link_values.png" alt="Selector item for module section" id="selector-circle-link" class="selector-circle-link"/>
            </a>
        </div>
    </div>
</div>

<slot></slot>