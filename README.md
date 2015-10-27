# Calculoid Google Gadget

Google Gadget is a small piece of HTML which can be inserted into [Google Sites](https://sites.google.com). Calculoid provides this gadget so users of Google Sites could be able to embed calculators from [Calculoid](http://calculoid.com) as well.

Google as a gadget library which would make adding the gadget very simple, but unfortunately, the link in their [documentation](https://developers.google.com/google-apps/sites/gadgets/site_gadgets#SubmitGadget) about how to submit a gadget to the library is broken and we couldn't find it elsewhere. Please, let us know if you find it. Fortunately, there is another way.

## How to add the Calculoid gadget to a Google Site?

If you haven't already, create a Google Site from https://sites.google.com. You can use any calculator from http://app.calculoid.com or create your own.

At the page detail:

1. Click on Edit button.
2. Select Insert > Gadgets > More gadgets.
3. Click on *Add gadget by URL*
4. Insert this URL: `http://app.calculoid.com/google-gadget/gadget.xml`
5. Confirm by clicking on Add button. Gadget configuration form appears.
6. Insert the ID of the calculator you want to add. You can find the ID (numeric) for example in the URL of the calculator at calculoid.com. eg `http://app.calculoid.com/#/calculator/64` means that ID is 64.
7. Insert your API key to get the benefits of your Calculoid account (view limits and so on).
8. Configure the rest of options as you'd like. You can get back later and change them.
9. Hit OK and then Save.

## [Live demo](https://sites.google.com/site/calculoidgadgetpreview/)
