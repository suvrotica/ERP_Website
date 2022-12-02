<script>
    import PageHeader from "../lib/PageHeader.svelte";
    import Navigation from "../lib/Navigation.svelte";
    import PageFooter from "../lib/PageFooter.svelte";
    export let PageHeaderInfo;

</script>

<PageHeader {PageHeaderInfo}/>
<Navigation />
<slot></slot>
<PageFooter/>