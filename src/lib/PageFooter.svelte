<script>
    import DownloadPdfButton from './brochureDownload.svelte';
  
    /**
   * @type {string}
   */
    let currentMonthYear;
  
    $: {
      const currentDate = new Date();
      const monthNames = ["January", "February", "March", "April", "May", "June",
        "July", "August", "September", "October", "November", "December"];
      const currentMonth = monthNames[currentDate.getMonth()];
      const currentYear = currentDate.getFullYear();
  
      currentMonthYear = `${currentMonth} ${currentYear}`;
    }
  </script>
  
  
  

<hr>
    <nav class="navbar sticky-top bg-light navbar-expand-md navbar-light">

        <div class="container-xxl">
            
            <DownloadPdfButton />
            <span class="small "><span><i class="bi bi-c-square-fill"></i></span>     Copyright {currentMonthYear} <i class="bi bi-file-earmark-lock2-fill"></i> </span>
            
            <a href="https://wa.me/+971502113555" target="_blank" rel="noreferrer"class="btn btn-sm btn-success text-light" ><i class="bi bi-whatsapp"></i> Whatsapp</a>
            

        </div>

    </nav>