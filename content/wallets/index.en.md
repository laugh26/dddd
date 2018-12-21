---
title: "Wallets"
date: 2018-03-20T08:09:08+13:00
draft: false
type: "default"
author: ""
description: "Cadex is an open source protocol, which means that wallets are maintained by a range of organizations and individuals"
---

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
{{< hero_section
titleText="Wallets"
imgSrc="/images/wallets/wal-hero.svg"
paragraphText="Cadex is an open source protocol, which means that wallets are maintained by a range of organizations and individuals. There are different types of wallets - from ‘full’ wallets that give you complete control and allow you to participate in the Cadex network, to 'light' wallets that are easier to use. Always remember that it is your responsibility to choose your wallet carefully and adopt good practices in order to protect your&nbsp;money."
buttonText="Ask community for assistance"
buttonImgSrc="/images/icons/rightward-arrow.svg"
buttonLink="https://discord.gg/y4Vu9jw"
newTab="true"
>}}

{{< item_container_section
    titleText="Cadex Wallets"
    subtitleText="Make sure to do your own research or ask community for&nbsp;assistance."
    >}}
    {{< wallet
        titleText="Cadex Core"
        walletImgSrc="/images/wallets/wal-core.png"
        text="Cadex Core wallet is a full Cadex client that allows users to participate in network staking. This is the official reference implementation published by the Cadex Core&nbsp;developers."
        buttonUrl="#download-core"
        buttonText="Download"
        buttonImgSrc="/images/icons/downward-arrow.svg"
        platformImg1Src="/images/platforms/mac.png"
        platformImg2Src="/images/platforms/windows.png"
        platformImg3Src="/images/platforms/linux.png"
    >}}
    {{< wallet
        titleText="NavPay"
        walletImgSrc="/images/wallets/wal-navpay.png"
        text="NavPay is an easy to use light wallet, that allows you to securely store your NAV. It's available across desktop and mobile, and doesn't take up gigabytes of storage."
        buttonUrl="https://cadex.xyz/projects/nav-pay/"
        buttonText="Download"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
        platformImg1Src="/images/platforms/android.png"
        platformImg2Src="/images/platforms/mac.png"
        platformImg3Src="/images/platforms/windows.png"
        platformImg4Src="/images/platforms/linux.png"
        platformImg5Src="/images/platforms/pwa.png"
        platformImg6Src="/images/platforms/web.png"
        newTab="true"
    >}}
    {{< wallet
        titleText="NEXT"
        walletImgSrc="/images/wallets/wal-next.png"
        text="A modern and stylish next generation wallet for Cadex. As well as staking, NEXT offers a simple interface to create and vote on community fund proposals."
        buttonUrl="http://next.navcommunity.net/"
        buttonText="Download"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
        platformImg1Src="/images/platforms/mac.png"
        platformImg2Src="/images/platforms/windows.png"
        platformImg3Src="/images/platforms/linux.png"
        newTab="true"
    >}}
    {{< wallet
        titleText="Coinomi"
        walletImgSrc="/images/wallets/wal-coinomi.png"
        text="Coinomi is a Security-First Multi-Asset Wallet for Bitcoin, Altcoins and&nbsp;Tokens."
        buttonUrl="https://www.coinomi.com/"
        buttonText="Download"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
        platformImg1Src="/images/platforms/mac.png"
        platformImg2Src="/images/platforms/android.png"
        newTab="true"
    >}}
    {{< wallet
        titleText="NavPi StakeBox"
        walletImgSrc="/images/wallets/wal-pi.png"
        text="A low-energy Cadex full wallet based on the Raspberry-Pi&nbsp;platform."
        buttonUrl="https://cadex.xyz/projects/nav-pi/"
        buttonText="Download"
        platformImg1Src="/images/platforms/pi.png"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
        newTab="true"
    >}}
    {{< wallet
        titleText="Cadex M8"
        walletImgSrc="/images/wallets/wal-m8.png"
        text="A high-powered Cadex staking wallet including NEXT Wallet with DIY&nbsp;options."
        buttonUrl="https://cadexm8.com/"
        buttonText="Learn More"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
        platformImg1Src="/images/platforms/linux.png"
        newTab="true"
    >}}
    {{< wallet
        titleText="NavPaper"
        walletImgSrc="/images/wallets/wal-paper.png"
        text="Generate keys to be printed and stored offline for additional&nbsp;security."
        buttonUrl="https://paper.cadex.xyz/"
        buttonText="Download"
        buttonImgSrc="/images/icons/rightward-arrow.svg"
        platformImg1Src="/images/platforms/mac.png"
        platformImg2Src="/images/platforms/windows.png"
        platformImg3Src="/images/platforms/web.png"
        newTab="true"
    >}}
{{< /item_container_section >}}

{{< item_container_section
    titleText="Download Cadex Core 4.4.0"
    subtitleText="The Cadex Core wallet has been carefully refined to be intuitive and easy to use. It comes with a setup wizard and everything you need to load the blockchain and start sending transactions in a secure&nbsp;environment."
    bgPurple="true"
    anchor="download-core"
    buttonUrl="https://github.com/NAVCoin/cadex-core/releases/latest"
    buttonText="Advanced Downloads"
    buttonImgSrc="/images/icons/rightward-arrow.svg"
    newTab="true"
>}}
    {{< action
        titleText="Windows"
        imgSrc="/images/wallets/wal-windows.svg"
        subtext=""
        linkText="Download"
        linkUrl="https://github.com/NAVCoin/cadex-core/releases/download/4.4.0/cadex-4.4.0-win64.zip"
        linkImgSrc="/images/icons/downward-arrow.svg"
    >}}
    {{< action
        titleText="Mac"
        imgSrc="/images/wallets/wal-mac.svg"
        subtext=""
        linkText="Download"
        linkUrl="https://github.com/NAVCoin/cadex-core/releases/download/4.4.0/cadex-4.4.0-osx.dmg"
        linkImgSrc="/images/icons/downward-arrow.svg"
    >}}
    {{< action                 
        titleText="Linux"
        imgSrc="/images/wallets/wal-linux.svg"
        subtext=""
        linkText="Download"
        linkUrl="https://github.com/NAVCoin/cadex-core/releases/download/4.4.0/cadex-4.4.0-x86_64-linux-gnu.tar.gz"
        linkImgSrc="/images/icons/downward-arrow.svg"
    >}}
{{< /item_container_section >}}


<script>
$("a[href^='#']").click(function(e) {
	e.preventDefault();

	var position = $($(this).attr("href")).offset().top;

	$("body, html").animate({
		scrollTop: position
	} /* speed */ );
});
</script>
