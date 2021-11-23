### Doing cards in markdown, a simple way

<style>
    cardContainer{
        width:100%;
        display:flex;
        flex-direction:row;
        justify-content:space-between;
    }

    cardc2bcontainer{
        width:30%;
        padding:10px;
        text-align:center;
        border-top:1px solid blue;
    }

    cardb2bcontainer{
        width:30%;
        padding:10px;
        text-align:center;
        border-top:1px solid green;
    }

    cardb2ccontainer{
        width:30%;
        padding:10px;
        text-align:center;
        border-top:1px solid pink;
    }

    cardc2b{
        width:50px;
        height:50px;
        border-radius:50%;
        padding:10px;
        text-align:center;
        background-color:blue;
        display:block;
        line-height:50px;
        margin:5px auto;
    }

    cardb2b{
        width:50px;
        height:50px;
        border-radius:50%;
        padding:10px;
        text-align:center;
        background-color:green;
        display:block;
        line-height:50px;
        margin:5px auto;
    }

    cardb2c{
        width:50px;
        height:50px;
        border-radius:50%;
        padding:10px;
        text-align:center;
        background-color:pink;
        display:block;
        line-height:50px;
        margin:5px auto;
    }

    cardLabel{
        color:white;
        font-size:16px;
    }

    cardHeading{
        font-size:20px;
        font-weight:bold;
        margin: 10px 0px;
        display:block;
    }

    cardText {
        font-size:17px;
        margin:5px;
        display:block;
    }
</style>

<cardContainer>

<cardc2bcontainer>

<cardc2b>
<cardLabel>
C2B
</caLabel>
</cardc2b>

<cardHeading>
C2B
</cardHeading>

<cardText>
C2B API is used by a business to receive payments through our payment gateway from the customers who purchase our products.
</cardText>

[Read more](https://link_to_some_external_docs)

</cardc2bcontainer>

<cardb2bcontainer>

<cardb2b>
<cardLabel>
B2B
</cardLabel>
</cardb2b>

<cardHeading>
B2B
</cardHeading>

<cardText>
B2B API will allow you to pay other businesses directly to their MPesa Paybill / Till number or IPay Merchant account.
</cardText>

[Read more](https://link_to_some_external_docs)

</cardb2bcontainer>

<cardb2ccontainer>

<cardb2c>
<cardLabel>
B2C
</cardLabel>
</cardb2c>

<cardHeading>
B2C
</cardHeading>

<cardText>
B2C API is a disbursement API that allows a business to pay directly to its customers through Mpesa, ...
</cardText>

[Read more](https://link_to_some_external_docs)

</cardb2ccontainer>

</cardContainer>
