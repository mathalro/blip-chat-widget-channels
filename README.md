# Blip Chat Widget Channels Addons

This is a complementary script to the [Blip Chat Widget](https://github.com/takenet/blip-chat-widget "Take Blip Chat Repository"). 

Using this code structure you can add a link for your WhatsApp Inteligent Contact and give the user an unique experience to talk with your brand using your site or your WhatsApp, the user chooses. 

## Expected Results

![Result](https://s3-sa-east-1.amazonaws.com/i.imgtake.takenet.com.br/iyexgr0n5l/iyexgr0n5l.gif)

## How to use

1 - First of all, you need to have an Inteligent Contact configured for Blip Chat channel in [Take Blip Platform](https://portal.blip.ai/ "Create your inteligent contact here"). If you don't know how to do this, you can follow [this tutorial](https://help.blip.ai/hc/pt-br/articles/360059366993-Como-adicionar-um-bot-em-um-site-utilizando-o-Blip-Chat- "Como adicionar um bot em um site utilizando o Blip Chat?") to create your first chatbot and use it in your site. 

2 - If you already acomplish the first step, you can start to use the blip chat channel addons. First, take a look at the code in [this repository](https://github.com/matheus-almeida-rosa/blip-chat-widget-channels/blob/master/index.html "blip-chat-widget-channels"). This is an example of how to use the code. You only need to add the **<style>** tag, the **<div class="channels-container" id="channels-container">** and the **<script>** tags to your website. Below you'll see how to add them and configure its dependencies. 

### Style tags

The beaty of the Blip Chat Widget Channels Addons is given by its styles. So you must copy the style of the example to your website in order to use it. You also must have some attention points:

* Make sure you added the styles in your website. It is not a problem to add it in another file, since you know what you are doing :) 
* Make sure your website styles does not match the style names of the styles that you're copying. If you change this, remember to update all its references in the rest of the code. 
* Replace the **background-color** field for parent (The first button that open the other channels), whatsapp (The button that redirects to whatsapp) and blipchat (The blip chat default behavior).

The image below shows the main items involved in this step

![Styles](https://s3-sa-east-1.amazonaws.com/i.imgtake.takenet.com.br/iecjruie5l/iecjruie5l.jpg)

### HTML

To add the new components, you just need to add the **<div class="channels-container" id="channels-container">** to your HTML, in order to show the new buttons. So, add it to your website. You do not need to change anything here. See the target content below.

![HTML Content](https://s3-sa-east-1.amazonaws.com/i.imgtake.takenet.com.br/iirwtm62cw/iirwtm62cw.jpg)

### Scripts

Now, all you need to do is copy the scripts and replace some references.

1 - Blip Chat Scripts

Here, you just need to worry about your access key. Copy all the block, like the image below.

![Blip Chat Scripts](https://s3-sa-east-1.amazonaws.com/i.imgtake.takenet.com.br/ifxpnwzihw/ifxpnwzihw.jpg)

2 - WhatsApp Scripts

In this step, you need to replace the **phoneNumber** (The number of your WhatsApp Business Account) and the **text** that you want users to send.

![WhatsApp Scripts](https://s3-sa-east-1.amazonaws.com/i.imgtake.takenet.com.br/ipe914lsw7/ipe914lsw7.jpg)


3 - Parent Scripts

Here you do not need to worry about replaces. Only copy all the Parent Scripts block :)

![Parent Scripts](https://s3-sa-east-1.amazonaws.com/i.imgtake.takenet.com.br/itqczusqyx/itqczusqyx.jpg)

## That is it!!!

If you have any doubts or dificulties, ask a question in [Take Blip Forum](https://forum.blip.ai/). 

Ir you find any bugs, problems or improvements, you can contribute with this project making a [Pull Request](https://github.com/matheus-almeida-rosa/blip-chat-widget-channels/pulls) or opening an [issue](https://github.com/matheus-almeida-rosa/blip-chat-widget-channels/issues).

Have a good code!