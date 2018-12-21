---
title: "For Developers"
date: 2018-03-20T07:41:22+13:00
draft: false
type: "default"
description: "Cadex is a free and open-source project to which anyone can contribute. Its design is the collaborative effort of developers from all around the world."
---
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
{{< hero_section
titleText="Cadex For Developers"
imgSrc="/images/for-developers/dev-hero.svg"
paragraphText="Cadex is a free and open-source project to which anyone can contribute. Its design is the collaborative effort of developers from all around the world. Our common goal is to improve the Cadex protocol and its surrounding software ecosystem. Everyone has the potential to make a positive impact, no matter what your skill&nbsp;level."
buttonText="Read developer manifesto"
buttonLink="/es/governance/#read-manifestos"
buttonImgSrc="/images/icons/rightward-arrow.svg"
>}}

{{< zig_section
titleText="Get Funded By The Cadex&nbsp;Network"
imgSrc="/images/for-developers/dev-get-involved.svg"
buttonText="Learn more"
buttonUrl="/community-fund"
buttonImgSrc="/images/icons/rightward-arrow.svg"
reversed="true"
>}}
Cadex’s Community Fund enables any developer to get paid by the network for their contributions to the Cadex ecosystem. Projects are funded and approved by the decentralized network with no central authority. This ensures Cadex’s direction remains firmly in the best interest of the network and is autonomously determined by the&nbsp;community.
{{< /zig_section>}}
{{< item_container_section 
    titleText="Why You Should Get Involved"
    subtitleText="Cadex is built for the community, by the community."
>}}
    {{< feature 
        titleText="Inclusive community"
        imgSrc="/images/for-developers/dev-community.svg"
        text="Our developer community is collaborative, inclusive, and ready to help you get&nbsp;started."
    >}}
    {{< feature 
        titleText="Active research"
        imgSrc="/images/for-developers/dev-cutting-edge.svg"
        text="Improvements to the Cadex protocol are constantly being worked&nbsp;on."
    >}}
    {{< feature                 
        titleText="Proof of Stake Alliance"
        imgSrc="/images/for-developers/dev-pos-alliance.svg"
        text="We’re part of the PoS Alliance, a consortium which aims to collaboratively research the PoS&nbsp;protocol."
    >}}
    {{< feature                 
        titleText="Easy to get started"
        imgSrc="/images/for-developers/dev-easy.svg"
        text="All the resources to get involved are at your fingertips and there are lots of ways to get&nbsp;involved."
    >}}
    {{< feature                 
        titleText="Programmable money"
        imgSrc="/images/for-developers/dev-digital-money.svg"
        text="With a publicly verifiable transaction ledger, you can easily use Cadex in your apps and&nbsp;websites."
    >}}
    {{< feature                 
        titleText="Always open-source"
        imgSrc="/images/for-developers/dev-trust.svg"
        text="Cadex software will always be free and in alignment with open-source&nbsp;principles."
    >}}
{{< /item_container_section >}}

{{< item_container_section 
    titleText="Contribute Now"
    subtitleText="There are many ways you can contribute to Cadex, no matter what your skill&nbsp;level."
    bgPurple="true"
>}}
    {{< long_text 
        titleText="Cadex Protocol"
        imgSrc="/images/for-developers/dev-protocol.svg"
        text="Cadex is open-source and everyone can participate in making it better. Here’s where you can find the procedures to report an issue, fix a issue or suggest an improvement to the consensus&nbsp;protocol."
        buttonUrl="/get-involved/"
        buttonText="Learn more"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
    >}}
    {{< long_text 
        titleText="Community Projects"
        imgSrc="/images/for-developers/dev-projects.svg"
        text="Cadex is more than just a protocol, it’s an ecosystem of websites, applications and devices which connect to the Cadex protocol. Here’s where you can find out about contributing to community&nbsp;projects."
        buttonUrl="https://cadex.xyz"
        buttonText="Learn more"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
    >}}
    {{< long_text 
        titleText="Responsible Disclosure"
        imgSrc="/images/for-developers/dev-disclosure.svg"
        text="Cadex is experimental technology and sometimes critical bugs are found. If you’re a researcher and you’ve found a critical vulnerability here’s how you can talk securely with the Cadex Core&nbsp;developers."
        buttonUrl="/responsible-disclosure/"
        buttonText="Learn more"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
    >}}
{{< /item_container_section >}}

{{< contrib_list
    titleText="Cadex Protocol Contributors"
    subtitleText="We would like to thank our contributors who have made this protocol&nbsp;awesome!"
    buttonUrl="https://github.com/NAVCoin/cadex-core/graphs/contributors"
    buttonTxt="View Cadex on GitHub"
    buttonImgSrc="/images/icons/rightward-arrow.svg"
>}}
<script>
$("a[href^='#']").click(function(e) {
	e.preventDefault();
	
	var position = $($(this).attr("href")).offset().top;

	$("body, html").animate({
		scrollTop: position
	} /* speed */ );
});
</script>