
Graph

Flutter Charts library

The Flutter Charts package is a data visualization library written natively in Dart for creating beautiful, animated and high-performance charts, which are used to craft high-quality mobile app user interfaces using Flutter.

Overview

Create various types of cartesian, circular and spark charts with seamless interaction, responsiveness, and smooth animation. It has a rich set of features, and it is completely customizable and extendable.

Chart types - Provides functionality for rendering 30+ chart types, namely line, spline, column, bar, area, bubble, box and whisker, scatter, step line, fast line, range column, range area, candle, hilo, ohlc, histogram, step area, spline area, spline range area, stacked area, stacked bar, stacked column, stacked line, 100% stacked area, 100% stacked bar, 100% stacked column, 100% stacked line, waterfall, pie, doughnut, radial bar, pyramid, funnel. Each chart type is easily configured and customized with built-in features for creating stunning visual effects.

Spark Charts features Spark charts (Sparkline charts) which is also known as micro charts are lightweight charts that fit in a very small area. They display the trend of the data and convey quick information to the user.

Chart getting started Import the following package.

import 'package:syncfusion_flutter_charts/charts.dart'; Add chart to the widget tree Add the chart widget as a child of any widget. Here, the chart widget is added as a child of container widget.

@override Widget build(BuildContext context) { return Scaffold( body: Center( child: Container( child: SfCartesianChart() ) ) ); } Note

Use SfCartesianChart widget to render line, spline, area, column, bar, bubble, scatter, step line, and fast line charts. Use SfCircularChart widget to render pie, doughnut, and radial bar charts. Use SfPyramidChart and SfFunnelChart to render pyramid and funnel charts respectively.

Spark Charts getting started Import the following package.

import 'package:syncfusion_flutter_charts/sparkcharts.dart'; Add spark charts to the widget tree Add the spark charts widget as a child of any widget. Here, the spark charts widget is added as a child of container widget.

@override Widget build(BuildContext context) { return Scaffold( body: Center( child: Container( child: SfSparkLineChart() ) ) ); } Note

Use SfSparkAreaChart, SfSparkBarChart and SfSparkWinLossChart widgets to render area, bar and win-loss charts respectively.

Output In Android:-




https://user-images.githubusercontent.com/107614710/187369645-4085bd23-bf8c-4c01-adca-a87305a5109e.mov




Output In IOS :-






https://user-images.githubusercontent.com/107614710/187369669-19ba3087-9eec-429c-909f-af371dbbab7e.mov






