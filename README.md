<div style="display: flex; flex-flow: row; margin-bottom: 1rem; font-family: 'Titillium Web'">
    <!-- <img style="border-radius: 0.25rem; align-self: center; justify-content: left; " alt="Infragistics" src="https://www.infragistics.com/media/441501/horz_logo.png"/> -->
    <!-- <img style="border-radius: 0.25rem; align-self: center; justify-content: left; " alt="Infragistics" src="https://raw.githubusercontent.com/Infragistics/docs-common/refs/heads/main/img/ig-title.svg"/> -->
</div>

![Infragistics repository title](./ig-title.svg)

# Infragistics Common Docs

This repository stores common files shared between the following help documentations:

- [Infragistics ASP-NET](https://github.com/Infragistics/docs-asp-net) repository
- [Infragistics WPF](https://github.com/Infragistics/docs-wpf) repository
- [Infragistics WPF-TA](https://github.com/Infragistics/docs-wpf-ta) repository
- [Infragistics Win-Forms](https://github.com/Infragistics/docs-win-forms) repository
- [Infragistics Win-Forms TA RTF](https://github.com/Infragistics/docs-win-forms-ta-rft) repository
- [Infragistics Win-Forms TA HP](https://github.com/Infragistics/docs-win-forms-ta-hp) repository


## Docs Configuration File

The DocsConfig.xml file contains configuration for all IG help docs:
- Products section contains definitions of products used for generating final product tables
- Variable section contains definitions of variables used in titles and content of topics (EN/JP locals)
- BuildFlags section contains definitions of build flags used for filtering nodes in TableWire and build flagging topic content in [TripWire](https://github.com/Infragistics/docs-tripwire)


## Types of Table of Content (TOC) files:

There are three types of [TOC](./TOC/) files:
- master*.toc file - table of content for each IG product
- shared*.toc file - table of content shared between IG product, e.g. cross-platform controls
- waw*.toc file - table of content shared between WinForms and Web products

## Shared Topics

The this repository contains shared topics for these components:

- [barcodes](./topics/en/barcodes)
- [bullet-graph](./topics/en/bullet-graph)
- [category-chart](./topics/en/category-chart)
- [data-chart](./topics/en/data-chart)
- [data-grid](./topics/en/data-grid)
- [data-pie-chart](./topics/en/data-pie-chart)
- [document-engine](./topics/en/document-engine)
- [donut-chart](./topics/en/donut-chart)
- [excel-engine](./topics/en/excel-engine)
- [financial-chart](./topics/en/financial-chart)
- [funnel-chart](./topics/en/funnel-chart)
- [geographic-map](./topics/en/geographic-map)
- [linear-gauge](./topics/en/linear-gauge)
- [pie-chart](./topics/en/pie-chart)
- [productivity-tools](./topics/en/productivity-tools)
- [radial-gauge](./topics/en/radial-gauge)
- [scheduler](./topics/en/scheduler)
- [shape-chart](./topics/en/shape-chart)
- [sparkline](./topics/en/sparkline)
- [spreadsheet](./topics/en/spreadsheet)
- [surface-chart](./topics/en/surface-chart)
- [win-web-chart](./topics/en/win-web-chart           )
<!-- 
## Topics Ported from IG DevOps Repositories

The following Azure DevOps repositories were ported to [topics](./topics/) folder:

- https://infragistics.visualstudio.com/NetAdvantage/_git/barcodes-docs-en              
- https://infragistics.visualstudio.com/NetAdvantage/_git/barcodes-docs-ja              
- https://infragistics.visualstudio.com/NetAdvantage/_git/bulletgraph-docs-en 
- https://infragistics.visualstudio.com/NetAdvantage/_git/bulletgraph-docs-ja           
- https://infragistics.visualstudio.com/NetAdvantage/_git/categorychart-docs-en        
- https://infragistics.visualstudio.com/NetAdvantage/_git/categorychart-docs-ja            
- https://infragistics.visualstudio.com/NetAdvantage/_git/data-pie-chart-docs-en        
- https://infragistics.visualstudio.com/NetAdvantage/_git/data-pie-chart-docs-ja           
- https://infragistics.visualstudio.com/NetAdvantage/_git/datachart-docs-en            
- https://infragistics.visualstudio.com/NetAdvantage/_git/datachart-docs-ja                
- https://infragistics.visualstudio.com/NetAdvantage/_git/documentengine-docs-en       
- https://infragistics.visualstudio.com/NetAdvantage/_git/documentengine-docs-ja         
- https://infragistics.visualstudio.com/NetAdvantage/_git/doughnutchart-docs-en         
- https://infragistics.visualstudio.com/NetAdvantage/_git/doughnutchart-docs-ja            
- https://infragistics.visualstudio.com/NetAdvantage/_git/excelengine-docs-en           
- https://infragistics.visualstudio.com/NetAdvantage/_git/excelengine-docs-ja              
- https://infragistics.visualstudio.com/NetAdvantage/_git/financialchart-docs-en           
- https://infragistics.visualstudio.com/NetAdvantage/_git/financialchart-docs-ja           
- https://infragistics.visualstudio.com/NetAdvantage/_git/funnelchart-docs-en           
- https://infragistics.visualstudio.com/NetAdvantage/_git/funnelchart-docs-ja              
- https://infragistics.visualstudio.com/NetAdvantage/_git/geographicmap-docs-en         
- https://infragistics.visualstudio.com/NetAdvantage/_git/geographicmap-docs-ja            
- https://infragistics.visualstudio.com/NetAdvantage/_git/lineargauge-docs-en           
- https://infragistics.visualstudio.com/NetAdvantage/_git/lineargauge-docs-ja              
- https://infragistics.visualstudio.com/NetAdvantage/_git/piechart-docs-en              
- https://infragistics.visualstudio.com/NetAdvantage/_git/piechart-docs-ja                 
- https://infragistics.visualstudio.com/NetAdvantage/_git/productivitytools-docs-en    
- https://infragistics.visualstudio.com/NetAdvantage/_git/productivitytools-docs-ja    
- https://infragistics.visualstudio.com/NetAdvantage/_git/radialgauge-docs-en          
- https://infragistics.visualstudio.com/NetAdvantage/_git/radialgauge-docs-ja              
- https://infragistics.visualstudio.com/NetAdvantage/_git/shapechart-docs-en               
- https://infragistics.visualstudio.com/NetAdvantage/_git/shapechart-docs-ja               
- https://infragistics.visualstudio.com/NetAdvantage/_git/sparkline-docs-en             
- https://infragistics.visualstudio.com/NetAdvantage/_git/sparkline-docs-ja                
- https://infragistics.visualstudio.com/NetAdvantage/_git/spreadsheet-docs-en           
- https://infragistics.visualstudio.com/NetAdvantage/_git/spreadsheet-docs-ja              
- https://infragistics.visualstudio.com/NetAdvantage/_git/surfacechart-docs-en             
- https://infragistics.visualstudio.com/NetAdvantage/_git/surfacechart-docs-ja             
- https://infragistics.visualstudio.com/NetAdvantage/_git/winweb-chart-docs-en   
- https://infragistics.visualstudio.com/NetAdvantage/_git/winweb-chart-docs-ja   
 -->
