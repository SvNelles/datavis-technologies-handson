<script>
    // Dimensions
    const width = 800;
    const height = 100;
    const margin = { top: 5, right: 5, bottom: 5, left: 5 };
    const innerWidth = width - margin.left - margin.right;
    const innerHeight = height - margin.top - margin.bottom;
  
    // Array
    const values = [2, 4, 6, 7, 9];

    // Import
    import { scaleLog} from "d3-scale";
    const scale = scaleLog();
  </script>
  
  <svg viewBox="0 0 {width} {height}">
    <g transform="translate({margin.left},{margin.top})">
      {#each values as item}
      // Did *100 for clarity
      <circle cx={scale(item)*100} cy={item} r="10"/>
      {/each}
    </g>
  </svg>
