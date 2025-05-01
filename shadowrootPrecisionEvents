const auroraLinkButton = document.querySelector('.score-hero .score-call-to-action .score-button');

const shadowRoot = auroraLinkButton.shadowRoot;

const cta = shadowRoot.querySelector('a.aurora-btn.primary');

if (cta) {
    cta.addEventListener('click', function (event) {
        freshpaint.track("CTA_hero",
            {
                "$options": {
                    integrations: {
                        'All': false,
                        'Google Analytics 4 Proxy::G-FRCNWCQM4Z': true,
                    }
                }
            }

        ); 
    });
};