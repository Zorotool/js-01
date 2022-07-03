@media screen and (min-width: 900px) {
  .section-team {
    background-color: orange;
  }
}


<picture>
                  <source
                    srcset="
                      ./images/team/person1-desktop.jpg    1x,
                      ./images/team/person1-desktop@2x.jpg 2x
                    "
                    media="(min-width:1200px)"
                  />
                  <source
                    srcset="
                      ./images/team/person1-tablet.jpg    1x,
                      ./images/team/person1-tablet@2x.jpg 2x
                    "
                    media="(min-width:768px)"
                  />
                  <source
                    srcset="
                      ./images/team/person1-mobile.jpg    1x,
                      ./images/team/person1-mobile@2x.jpg 2x
                    "
                    media="(min-width:480px)"
                  />
                  <img
                    class="display-block stretchable"
                    src="./images/team/person1-mobile.jpg"
                    width="450"
                    alt="Улыбчивый чувак в очках"
                  />
                </picture>

