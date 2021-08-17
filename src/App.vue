<template>
 <ejs-listview id='sample-list-flat' :dataSource='data' showCheckBox='true'></ejs-listview>
</template>

<script>
import "../node_modules/@syncfusion/ej2-base/styles/material.css";
import "../node_modules/@syncfusion/ej2-vue-buttons/styles/material.css";
import "../node_modules/@syncfusion/ej2-vue-lists/styles/material.css";

import { ListViewComponent } from "@syncfusion/ej2-vue-lists";

export default {
    name: "App",
    components: {
      "ejs-listview": ListViewComponent
    },
    data() {
    return {
      data: [
        { text: 'Hennessey Venom', id: 'list-01' },
        { text: 'Bugatti Chiron', id: 'list-02' },
        { text: 'Bugatti Veyron Super Sport', id: 'list-03' },
        { text: 'SSC Ultimate Aero', id: 'list-04' },
        { text: 'Koenigsegg CCR', id: 'list-05' },
        { text: 'McLaren F1', id: 'list-06' },
        { text: 'Aston Martin One- 77', id: 'list-07' },
        { text: 'Jaguar XJ220', id: 'list-08' },
        { text: 'McLaren P1', id: 'list-09' },
        { text: 'Ferrari LaFerrari', id: 'list-10' },
      ],
    };
  }
}
</script>
