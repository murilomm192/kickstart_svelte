<script lang="ts">
    import { Button } from "$lib/components/ui/button/index.js";
    import { getLocalTimeZone, today } from "@internationalized/date";
    import { Calendar } from "$lib/components/ui/calendar/index.js";

    let value = today(getLocalTimeZone());
  </script>
   
  <Button>Button</Button>

  <Calendar bind:value class="rounded-md border shadow" />