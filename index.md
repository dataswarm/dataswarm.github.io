---
layout: page
title: DataSwarm
tagline: Less Development, More analysis!
---
{% include JB/setup %}

<div>

  <!-- Nav tabs -->
  <ul class="nav nav-tabs" role="tablist">
    <li role="presentation" class="active"><a href="#notebook" aria-controls="notebook" role="tab" data-toggle="tab">Notebook</a></li>
    <li role="presentation"><a href="#infrastructure" aria-controls="infrastructure" role="tab" data-toggle="tab">Infrastructure</a></li>
    <li role="presentation"><a href="#language" aria-controls="language" role="tab" data-toggle="tab">Language</a></li>
    <li role="presentation"><a href="#versions" aria-controls="versions" role="tab" data-toggle="tab">Versions</a></li>
    <li role="presentation"><a href="#visualization" aria-controls="visualization" role="tab" data-toggle="tab">Visualization</a></li>
  </ul>

  <!-- Tab panes -->
  <div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="notebook">
      <div class="col-md-5">
        <h2>Multi-purpose Notebook</h2>

        <p style="font-size:16px; color:#555555;font-style:italic;margin-bottom: 15px;">
          The Notebook is the place for all your needs
        </p>
        <ul style="list-style-type: none;padding-left:10px;" >
          <li style="font-size:20px; margin: 5px;"><span class="glyphicon glyphicon-import"></span> Data Ingestion</li>
          <li style="font-size:20px; margin: 5px;"><span class="glyphicon glyphicon-eye-open"></span> Data Discovery</li>
          <li style="font-size:20px; margin: 5px;"><span class="glyphicon glyphicon-wrench"></span> Data Analytics</li>
          <li style="font-size:20px; margin: 5px;"><span class="glyphicon glyphicon-dashboard"></span> Data Visualization & Collaboration</li>
        </ul>
      </div>
      <br />
         <div class="col-md-7"><img class="img-responsive" style="border: 1px solid #ecf0f1;" height="auto" src="assets/themes/zeppelin/img/screenshots/chart.png" />
      </div>


    </div>
    <div role="tabpanel" class="tab-pane" id="infrastructure">
      <div class="col-md-5">
        <h2>Infrastructure</h2>

        <p style="font-size:16px; color:#555555;font-style:italic;margin-bottom: 15px;">
          Provide infrastructure was never easier
        </p>
        <ul style="list-style-type: none;padding-left:10px;" >
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/spark.png"/> Apache Spark</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/hadoop.png"/> Apache Hadoop</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/redshift.svg" /></span> AWS Redshift</li>
        </ul>
      </div>
      <br />
      <div class="col-md-7" style="margin-top: 15px;"><img class="img-responsive" style="border: 1px solid #ecf0f1;" height="auto" src="assets/themes/zeppelin/img/screenshots/cluster.png" /></div>
    </div>
    <div role="tabpanel" class="tab-pane" id="language">
      <div class="col-md-5">
        <h2>Connectors</h2>

        <p style="font-size:16px; color:#555555;font-style:italic;margin-bottom: 15px;">
          Many connectors is available
        </p>
        <ul style="list-style-type: none;padding-left:10px;" >
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/spark.png"/> Apache Spark</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/hadoop.png"/> Apache Hive</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/redshift.svg" /></span> Redshift</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/luigi.png" /></span> Luigi</li>
        </ul>
      </div>
      <div class="col-md-7" style="margin-top: 75px;">
        </br>
        <ul style="list-style-type: none;padding-left:10px;" >
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/scala.png" /></span> Scala</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/angular.jpg" /></span> Angular</li>
          <li style="font-size:20px; margin: 5px;"><img class="glyphicon" src="assets/themes/zeppelin/img/shell.png" /></span> Shell</li>
          <li style="font-size:20px; margin: 5px;"></span> Comming more</li>

        </ul>
      </div>
    
    </div>

    <div role="tabpanel" class="tab-pane" id="versions">
      <div class="col-md-5">
        <h2>Control versions</h2>

        DataSwarm provides version control using gist. You can keep adding reviews and switch between they.

      </div>
      <br />
      <div class="col-md-7" style="margin-top: 15px;"><img class="img-responsive" style="border: 1px solid #ecf0f1;" height="auto" src="assets/themes/zeppelin/img/screenshots/gist.png" /></div>

    </div>
    <div role="tabpanel" class="tab-pane" id="visualization">
      <br />
      <h2>Data visualization</h2>

      Some basic charts are already included in DataSwarm. Visualizations are not limited to SparkSQL's query, any output from any language backend can be recognized and visualized.

      <div class="row">
        <div class="col-md-6">
          <img class="img-responsive" src="./assets/themes/zeppelin/img/graph1.png" />
        </div>
        <div class="col-md-6">
          <img class="img-responsive" src="./assets/themes/zeppelin/img/graph2.png" />
        </div>
      </div>

      <h3>Pivot chart</h3>

      With simple drag and drop DataSwarm aggeregates the values and display them in pivot chart. You can easily create chart with multiple aggregated values including sum, count, average, min, max.

      <div class="row">
        <div class="col-md-8">
          <img class="img-responsive" src="./assets/themes/zeppelin/img/screenshots/pivot.png" />
        </div>
      </div>
    </div>
  </div>
</div>