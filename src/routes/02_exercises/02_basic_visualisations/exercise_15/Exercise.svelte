<script>
    const width = 100;
    const height = 100;
    const margin = { top: 5, right: 5, bottom: 5, left: 5 };
    const innerWidth = width - margin.left - margin.right;
    const innerHeight = height - margin.top - margin.bottom;
  </script>
  
  <svg {width} {height}>
    <g transform="translate({margin.left}, {margin.top})">
      <!--  -->
    </g>
    <rect x=30 y=30 width=40 height=40 color="yellow"/>
    <circle cx=70 cy=70 r=20 />
  </svg>
  
  <style>
    svg {
      border: 1px solid black;
      border-radius: 5px;
    }
            rect {
            fill: yellow;
          }
                  circle {
            fill: skyblue;
        }
  </style>
  