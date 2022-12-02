<script>
    import PageHeader from "../lib/PageHeader.svelte";
    import Navigation from "../lib/Navigation.svelte";
    import PageFooter from "../lib/PageFooter.svelte";
    let PageHeaderInfo=["Premium UAE ERP solutions","+971 2 555 8686","+971 50 211 3555","sales@shertatechservices.com"]

</script>

<PageHeader {PageHeaderInfo}/>
<Navigation />
<slot></slot>
<PageFooter/>