<template>
    <div class="wrapper wrapper-content">
        <div class="row">
            <div id="reportrange" class="pull-right text-center" style="background: #fff; cursor: pointer; padding: 12px 10px; border: 1px solid #ccc; width:300px;margin-bottom:20px;margin-right: 15px;">
                <i class="fa fa-calendar"></i>&nbsp;
                <span></span> <b class="caret"></b>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-3">
                <div class="ibox float-e-margins">
                    <div class="ibox-title">
                        <span class="label label-success pull-right">This Month</span>
                        <h5>Income</h5>
                    </div>
                    <div class="ibox-content">
                        <h1 class="no-margins">$22,221</h1>

                        <div class="stat-percent font-bold text-success">98% <i class="fa fa-bolt"></i></div>
                        <small>Total income</small>
                    </div>
                </div>
            </div>
            <div class="col-lg-3">
                <div class="ibox float-e-margins">
                    <div class="ibox-title">
                        <span class="label label-success pull-right">This Month</span>
                        <h5>Cycle Time</h5>
                    </div>
                    <div class="ibox-content">
                        <h1 class="no-margins">2.1</h1>

                        <div class="stat-percent font-bold text-info">10% <i class="fa fa-level-down"></i></div>
                        <small>Days</small>
                    </div>
                </div>
            </div>
            <div class="col-lg-3">
                <div class="ibox float-e-margins">
                    <div class="ibox-title">
                        <span class="label label-primary pull-right">Today</span>
                        <h5>New Assignments</h5>
                    </div>
                    <div class="ibox-content">
                        <h1 class="no-margins">12</h1>

                        <div class="stat-percent font-bold text-navy">44% <i class="fa fa-level-up"></i></div>
                        <small>New Appraisal Request</small>
                    </div>
                </div>
            </div>
            <div class="col-lg-3">
                <div class="ibox float-e-margins">
                    <div class="ibox-title">
                        <span class="label label-primary pull-right">Open Task</span>
                        <h5>Open Task Items</h5>
                    </div>
                    <div class="ibox-content">
                        <h1 class="no-margins">10</h1>

                        <small>In first month</small>
                    </div>
                </div>
            </div>
        </div>
        <div class="row" style="margin-bottom:20px;">
            <div class="form-group">
                                  

                <div id="statusselector" class="">
                    <label class="col-md-12 control-label">Assignment Type Filter:</label>
                    <div class="col-md-2">
                        <select class="form-control" id="selectorstatus">
                                                <option>All Status Types</option>
                                              <option>New Assignments</option>
                                              <option>Scheduled</option>
                                              <option>Inspected</option>
                                              <option>Billed</option>
                                              <option>Overdue</option>
                                              <option>Paid</option>
                                              <option>Cancelled</option>
                                              </select>
                    </div>
                </div>
            </div>
        </div>


        <div class="row">

            <div class="col-lg-12">


                <div class="ibox float-e-margins">
                    <div class="ibox-title">
                        <h5>Assignments</h5>
                    </div>

                    <div class="table-responsive">
                        <table class="table table-striped table-bordered table-condensed table-hover">
                            <tbody>
                                <tr>
                                    <th>Status</th>
                                    <th>Index #</th>
                                    <th>Owner</th>
                                    <th>Claim #</th>
                                    <th>Vehicle</th>
                                    <th>Date Requested</th>
                                    <th>Date Inspected</th>
                                    <th>City, State</th>
                                    <th>Days Open</th>
                                    <th>Appraiser</th>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-warning">In Progress</span></td>
                                    <td><a href="/claim">115122ALO</a></td>
                                    <td>Tom Smith</td>
                                    <td>60002342342383-1-1</td>
                                    <td>2007 Toyota 4Runner</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Portland, OR</td>
                                    <td>5</td>
                                    <td>Kevin</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-warning">In Progress</span></td>
                                    <td>115122ALO</td>
                                    <td>Tom Smith</td>
                                    <td>60002342342383-1-1</td>
                                    <td>2007 Toyota 4Runner</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Clackamas, OR</td>
                                    <td>5</td>
                                    <td>Kevin</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-warning">In Progress</span></td>
                                    <td>115122ALO</td>
                                    <td>Tom Smith</td>
                                    <td>60002342342383-1-1</td>
                                    <td>2007 Toyota 4Runner</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Longview, WA</td>
                                    <td>5</td>
                                    <td>Kevin</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-primary">Assigned</span></td>
                                    <td>115122ALO</td>
                                    <td>Nick Anderson</td>
                                    <td>6330013232342383-1-1</td>
                                    <td>2003 Ford F-350</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Portland, OR</td>
                                    <td>5</td>
                                    <td>None</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-primary">Assigned</span></td>
                                    <td>115122ALO</td>
                                    <td>Nick Anderson</td>
                                    <td>6330013232342383-1-1</td>
                                    <td>2003 Ford F-350</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Dalles, OR</td>
                                    <td>5</td>
                                    <td>None</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-primary">Assigned</span></td>
                                    <td>115122ALO</td>
                                    <td>Nick Anderson</td>
                                    <td>6330013232342383-1-1</td>
                                    <td>2003 Ford F-350</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Happy Valley, OR</td>
                                    <td>5</td>
                                    <td>None</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-primary">Assigned</span></td>
                                    <td>115122ALO</td>
                                    <td>Kevin Keeland</td>
                                    <td>63332342342383-13-1</td>
                                    <td>2004 Toyota Camry</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Vancouver, WA</td>
                                    <td>5</td>
                                    <td>None</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-primary">Assigned</span></td>
                                    <td>115122ALO</td>
                                    <td>John Doeses</td>
                                    <td>60002342323323-3-2</td>
                                    <td>2011 Cheverolet Traverse</td>
                                    <td>06/06/16</td>
                                    <td>Incomplete</td>
                                    <td>Vancouver, WA</td>
                                    <td>5</td>
                                    <td>None</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-default">Inspected</span></td>
                                    <td>115122ALO</td>
                                    <td>Todd Sower</td>
                                    <td>H123242A2323</td>
                                    <td>2010 Dodge Ram</td>
                                    <td>06/06/16</td>
                                    <td>06/06/16</td>
                                    <td>Portland, OR</td>
                                    <td>5</td>
                                    <td>Brandon</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-default">Inspected</span></td>
                                    <td>115122ALO</td>
                                    <td>Mike Haeman</td>
                                    <td>H123242A2323</td>
                                    <td>2009 Jeep Cherokee</td>
                                    <td>06/06/16</td>
                                    <td>06/06/16</td>
                                    <td>Lake Oswego, OR</td>
                                    <td>5</td>
                                    <td>Brandon</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-default">Inspected</span></td>
                                    <td>115122ALO</td>
                                    <td>Mary Poppins</td>
                                    <td>H123242A2323</td>
                                    <td>2010 BMW 540i</td>
                                    <td>06/06/16</td>
                                    <td>06/06/16</td>
                                    <td>Portland, OR</td>
                                    <td>5</td>
                                    <td>Brandon</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-danger">Overdue</span></td>
                                    <td>115122ALO</td>
                                    <td>Dario Jawefwf</td>
                                    <td>23422342342383</td>
                                    <td>2001 Kia Sportage</td>
                                    <td>06/06/16</td>
                                    <td>06/06/16</td>
                                    <td>Portland, OR</td>
                                    <td>5</td>
                                    <td>Brandon</td>
                                </tr>
                                <tr class="">
                                    <td><span class="label label-success">Paid</span></td>
                                    <td>115122ALO</td>
                                    <td>Doe</td>
                                    <td>60002342342383-1-1</td>
                                    <td>2010 Ford Ranger</td>
                                    <td>06/06/16</td>
                                    <td>06/06/16</td>
                                    <td>Lake Oswego, OR</td>
                                    <td>5</td>
                                    <td>Brandon</td>
                                </tr>
                            </tbody>
                        </table>

                        <nav>
                            <ul class="pagination">
                                <li class="disabled"><a href="#" aria-label="Previous"><span aria-hidden="true">&laquo;</span></a></li>
                                <li class="active"><a href="#">1 <span class="sr-only">(current)</span></a></li>
                                <li class=""><a href="#">2 <span class="sr-only"></span></a></li>
                                <li class=""><a href="#" aria-label="Next"><span aria-hidden="true">&raquo;</span></a></li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </div>

        </div>



    </div>
</template>

<script>
    import moment from 'moment';


    export default {
        meteor: {
            data: {
                now: function () {
                    var now = moment().format('MM-DD-YY');
                    return now;
                },
                startnumber() {
                    var startnumber = moment().subtract(29, 'days');
                    return startnumber;
                }
            }
        },
        mounted() {
            var start = moment().subtract(29, 'days');
            var end = moment();

            function cb(start, end) {
                $('#reportrange span').html(start.format('MMMM D, YYYY') + ' - ' + end.format('MMMM D, YYYY'));
            }

            $('#reportrange').daterangepicker({
                startDate: start,
                endDate: end,
                ranges: {
                    'Today': [moment(), moment()],
                    'Yesterday': [moment().subtract(1, 'days'), moment().subtract(1, 'days')],
                    'Last 7 Days': [moment().subtract(6, 'days'), moment()],
                    'Last 30 Days': [moment().subtract(29, 'days'), moment()],
                    'This Month': [moment().startOf('month'), moment().endOf('month')],
                    'Last Month': [moment().subtract(1, 'month').startOf('month'), moment().subtract(1, 'month').endOf('month')]
                }
            }, cb);

            cb(start, end);

        }
    };

</script>