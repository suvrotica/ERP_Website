<script>
    import PageHeader from "../lib/PageHeader.svelte";
    import Navigation from "../lib/Navigation.svelte";
    import PageFooter from "../lib/PageFooter.svelte";
    import Analytics from "../lib/analytics.svelte";
    export let PageHeaderInfo;

</script>

<PageHeader {PageHeaderInfo}/>
<Navigation />
<Analytics />
<slot></slot>
<PageFooter/>