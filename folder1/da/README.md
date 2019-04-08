Array
(
    [0] => PostprocessCsvToResxScript
    [1] => Crowdin\App\MVC\Models\source Object
        (
            [_hasOne:protected] => Array
                (
                    [file] => Array
                        (
                            [field] => file_id
                            [class] => Crowdin\App\MVC\Models\file
                        )

                    [language] => Array
                        (
                            [field] => language_id
                            [class] => Crowdin\App\MVC\Models\language
                            [general_db] => 1
                        )

                )

            [_hasMany:protected] => Array
                (
                    [translations] => Array
                        (
                            [field] => source_id
                            [class] => Crowdin\App\MVC\Models\translation
                        )

                )

            [revertInfo:Crowdin\App\MVC\Models\source:private] => 
            [project:Crowdin\App\MVC\Models\source:private] => 
            [parallel_lock_key:Crowdin\App\MVC\Models\source:private] => 
            [is_action_allowed:Crowdin\App\MVC\Models\source:private] => 
            [_db:protected] => Crowdin\App\Src\DatabaseGateway\DatabaseGateway Object
                (
                    [connectionId:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => mysqli Object
                        (
                            [affected_rows] => 0
                            [client_info] => mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $
                            [client_version] => 50012
                            [connect_errno] => 0
                            [connect_error] => 
                            [errno] => 0
                            [error] => 
                            [error_list] => Array
                                (
                                )

                            [field_count] => 6
                            [host_info] => 192.168.1.203 via TCP/IP
                            [info] => 
                            [insert_id] => 0
                            [server_info] => 5.6.25-log
                            [server_version] => 50625
                            [stat] => Uptime: 1035075  Threads: 5  Questions: 53260400  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455
                            [sqlstate] => 00000
                            [protocol_version] => 10
                            [thread_id] => 980913
                            [warning_count] => 0
                        )

                    [connectedAt:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 1554730765
                    [config:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => Array
                        (
                            [host] => 192.168.1.203
                            [database] => crowdin_13616315
                            [user] => crowdin
                            [password] => superpuper
                            [port] => 
                        )

                    [lastErrorCode:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 0
                    [lastErrorMessage:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 
                    [retryIndex:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 0
                    [isTransaction:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 
                    [transactionQueries:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => Array
                        (
                        )

                    [currentQueryIndex:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => -1
                    [handledErrors:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => Array
                        (
                        )

                )

            [_cacheTTL:protected] => 0
            [_isNew:protected] => 
            [_localizedFields:protected] => Array
                (
                )

            [_localizedRow:protected] => Array
                (
                )

            [_dbTableName:Crowdin\App\Src\ActiveRecord\ActiveRecord:private] => source
            [id] => 1535
            [file_id] => 1828
            [language_id] => 58
            [type] => 0
            [path] => /13616315/287343/1535.md
            [revision] => 1
            [parent] => 0
            [words_count] => 2
            [scheme] => 
            [__file] => Crowdin\App\MVC\Models\file Object
                (
                    [_hasOne:protected] => Array
                        (
                            [project] => Array
                                (
                                    [field] => project_id
                                    [class] => Crowdin\App\MVC\Models\project
                                    [namespace_db] => 1
                                )

                            [source] => Array
                                (
                                    [field] => file_id
                                    [class] => Crowdin\App\MVC\Models\source
                                )

                        )

                    [_hasMany:protected] => Array
                        (
                            [sources] => Array
                                (
                                    [field] => file_id
                                    [class] => Crowdin\App\MVC\Models\source
                                )

                        )

                    [_db:protected] => Crowdin\App\Src\DatabaseGateway\DatabaseGateway Object
                        (
                            [connectionId:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => mysqli Object
                                (
                                    [affected_rows] => -1
                                    [client_info] => mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $
                                    [client_version] => 50012
                                    [connect_errno] => 0
                                    [connect_error] => 
                                    [errno] => 0
                                    [error] => 
                                    [error_list] => Array
                                        (
                                        )

                                    [field_count] => 6
                                    [host_info] => 192.168.1.203 via TCP/IP
                                    [info] => 
                                    [insert_id] => 0
                                    [server_info] => 5.6.25-log
                                    [server_version] => 50625
                                    [stat] => Uptime: 1035075  Threads: 6  Questions: 53260402  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455
                                    [sqlstate] => 00000
                                    [protocol_version] => 10
                                    [thread_id] => 980913
                                    [warning_count] => 0
                                )

                            [connectedAt:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 1554730765
                            [config:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => Array
                                (
                                    [host] => 192.168.1.203
                                    [database] => crowdin_13616315
                                    [user] => crowdin
                                    [password] => superpuper
                                    [port] => 
                                )

                            [lastErrorCode:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 0
                            [lastErrorMessage:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 
                            [retryIndex:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 0
                            [isTransaction:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => 
                            [transactionQueries:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => Array
                                (
                                )

                            [currentQueryIndex:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => -1
                            [handledErrors:Crowdin\App\Src\DatabaseGateway\DatabaseGateway:private] => Array
                                (
                                )

                        )

                    [_cacheTTL:protected] => 0
                    [_isNew:protected] => 
                    [_localizedFields:protected] => Array
                        (
                        )

                    [_localizedRow:protected] => Array
                        (
                        )

                    [_dbTableName:Crowdin\App\Src\ActiveRecord\ActiveRecord:private] => file
                    [id] => 1828
                    [project_id] => 287343
                    [draft_project_id] => 
                    [parent_id] => 1825
                    [name] => README.md
                    [type] => md14
                    [node_type] => 1
                    [status] => 1
                    [priority] => 1
                    [attributes] => a:2:{s:9:"mime_type";s:10:"text/plain";s:8:"filesize";i:20;}
                    [export_pattern] => /folder1/%two_letters_code%/%original_file_name%
                    [created] => 2019-04-08 15:53:18
                    [modified] => 2019-04-08 15:53:19
                    [last_accessed] => 
                    [title] => 
                )

        )

    [2] => /home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md
    [3] => Array
        (
            [language_id] => 10
            [export_options] => Array
                (
                    [1] => 1
                    [2] => 1
                    [3] => 1
                )

        )

)
<br />
<font size='1'><table class='xdebug-error xe-warning' dir='ltr' border='1' cellspacing='0' cellpadding='1'>
<tr><th align='left' bgcolor='#f57900' colspan="5"><span style='background-color: #cc0000; color: #fce94f; font-size: x-large;'>( ! )</span> Warning: Cannot modify header information - headers already sent by (output started at /home/crowdin/valeriy/crowdin-backend/modules/Exporters/ExportFactory.php:837) in /home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php on line <i>2426</i></th></tr>
<tr><th align='left' bgcolor='#e9b96e' colspan='5'>Call Stack</th></tr>
<tr><th align='center' bgcolor='#eeeeec'>#</th><th align='left' bgcolor='#eeeeec'>Time</th><th align='left' bgcolor='#eeeeec'>Memory</th><th align='left' bgcolor='#eeeeec'>Function</th><th align='left' bgcolor='#eeeeec'>Location</th></tr>
<tr><td bgcolor='#eeeeec' align='center'>1</td><td bgcolor='#eeeeec' align='center'>0.0001</td><td bgcolor='#eeeeec' align='right'>360080</td><td bgcolor='#eeeeec'>{main}(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>0</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>2</td><td bgcolor='#eeeeec' align='center'>0.0252</td><td bgcolor='#eeeeec' align='right'>4627624</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Application->run(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>9</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>3</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Application.php' bgcolor='#eeeeec'>.../Application.php<b>:</b>88</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>4</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>147</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>5</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6173856</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->do_export_file(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/Controller.php' bgcolor='#eeeeec'>.../Controller.php<b>:</b>110</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>6</td><td bgcolor='#eeeeec' align='center'>0.5960</td><td bgcolor='#eeeeec' align='right'>16262680</td><td bgcolor='#eeeeec'><a href='http://www.php.net/function.header' target='_new'>header</a>
(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>2426</td></tr>
<tr><th align='left' colspan='5' bgcolor='#e9b96e'>Variables in local scope (#5)</th></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$approvedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$attributes&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>array</b> <i>(size=2)</i>
  'mime_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
  'filesize' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>20</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$e&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$etag&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'af8b063373c53c5eae5c6a088f98b8e2'</font> <i>(length=32)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exception&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exporter&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
  <i>protected</i> 'source' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\source</i>)[<i>72</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'file' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
          'language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'translations' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\translation'</font> <i>(length=34)</i>
      <i>private</i> 'revertInfo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'project' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'parallel_lock_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'is_action_allowed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>79</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 6  Questions: 53260420  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source'</font> <i>(length=6)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
      <i>public</i> 'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
      <i>public</i> 'language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'path' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/13616315/287343/1535.md'</font> <i>(length=24)</i>
      <i>public</i> 'revision' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'parent' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'words_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'scheme' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> '__file' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\file</i>)[<i>73</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'project' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'source' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'sources' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>79</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
          <i>public</i> 'project_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
          <i>public</i> 'draft_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
          <i>public</i> 'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'priority' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
          <i>public</i> 'export_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/folder1/%two_letters_code%/%original_file_name%'</font> <i>(length=48)</i>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:18'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:19'</font> <i>(length=19)</i>
          <i>public</i> 'last_accessed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'title' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> '__project' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>168</i>]
              <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=6)</i>
                  ...
              <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
                  ...
              <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
              <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
              <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
              <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
              <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
              <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
              <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
              <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
              <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
              <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
              <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
              <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
              <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>protected</i> 'target_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>86</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260424  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1030'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'6'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe'</font> <i>(length=6)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'438'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'dan'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da-DK'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project_languages' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>protected</i> 'user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>74</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260425  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
      <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=6)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'group' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'workflow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'source_language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'childs' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'files' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260426  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
      <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
      <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
      <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
      <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
      <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
      <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'info' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'projects' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'groups' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'notification_channels' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
          <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
          <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
          <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
          <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
          <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
          <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
          <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
          <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
          <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
          <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
          <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'user' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'parent' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'organization' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
          <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
          <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
          <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
          <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
          <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
          <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
          <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
          <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
          <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
          <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
          <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
          <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
          <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
          <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
          <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
          <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
          <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
          <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> '_target_directory' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'plurals_mapping' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      5 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
  <i>protected</i> 'max_workflow_step_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'sources' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'export_option_translate_duplicates' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_approved_only' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_translate_dialects' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_suggestions' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      1 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      2 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      3 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_statistic' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'start' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      'end' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730766</font>
  <i>protected</i> 'exporter' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>md14_exporter</i>)[<i>172</i>]
      <i>protected</i> 'marker_tag_li' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'-'</font> <i>(length=1)</i>
      <i>protected</i> 'htmlExporter' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>html11_exporter</i>)[<i>163</i>]
          <i>protected</i> 'sourceFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/importer/13616315/287343/1535.md.html'</font> <i>(length=79)</i>
          <i>protected</i> 'resulted_file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
          <i>protected</i> 'webXmlExport' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> 'parser' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>html11_parser</i>)[<i>216</i>]
              <i>protected</i> 'html_inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=15)</i>
                  ...
              <i>protected</i> 'is_translatable_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/^[%^&amp;*@#~&gt;&lt;|=_+-]+$/'</font> <i>(length=21)</i>
              <i>protected</i> 'inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=24)</i>
                  ...
              <i>protected</i> 'nodeIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>7</font>
              <i>protected</i> 'translationIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>2</font>
              <i>protected</i> 'madCapMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xml2Mode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'webXmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'translateContent' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translateAttributes' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translatableElements' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> 'contentSegmentation' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'html' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>simple_html_dom</i>)[<i>207</i>]
                  ...
              <i>private</i> 'data' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'mask_phrases_in_html' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'segmentation' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\Utils\SrxSegmentation</i>)[<i>120</i>]
                  ...
              <i>private</i> 'export_file' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
              <i>protected</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
                <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
            <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> 'resultedFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
      <i>protected</i> 'iframe_helpers' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'listMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> 'listLineEndingsMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
        <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
      <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'pseudolocalization' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'last_translation' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886300'</font> <i>(length=6)</i>
      'text' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'int_test'</font> <i>(length=8)</i>
      'duplicate_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886299'</font> <i>(length=6)</i>
      'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:8:{s:6:&quot;hidden&quot;;b:0;s:11:&quot;description&quot;;s:14:&quot;Paragraph text&quot;;s:9:&quot;attribute&quot;;b:0;s:4:&quot;path&quot;;s:2:&quot;/p&quot;;s:10:&quot;identifier&quot;;s:32:&quot;b86493d2ae255a02bb7ea61e7fb77c10&quot;;s:8:&quot;rtrimmed&quot;;s:0:&quot;&quot;;s:8:&quot;ltrimmed&quot;;s:0:&quot;&quot;;s:5:&quot;index&quot;;i:5;}'</font> <i>(length=222)</i>
      'context' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Paragraph text&#13;&#10;XPath: /p'</font> <i>(length=25)</i>
      'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'last_translation_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'untranslated'</font> <i>(length=12)</i>
  <i>private</i> 'last_suggestion' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'icu_parser' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'placeholdersRegExp' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/&amp;[a-z_]+&amp;|\B%(?:\d+\$)*#@[^@]+@(?:(?![\p{L}\d])|$)|\{\$\w+\}|\[\/?[%\w\.-]+\]|\B\:[\w\.-]+\:\B|\$[\w\.!+-]+\$|\$\([\w\.-]+\)|\#\{[\w\.\$-]+\}\#?(?!\{)|\$\{[\w\.-]+\}\$?(?![\{\(\[])|\b__\w+__\b|\*\|.*?\|\*|\\\(\w+\)|(?:\{{3}\s?[\w\.\|+-]+\s?\}{3}|\{{2}\s?[\w\.\|+-]+\s?\}{2}|\{\s?[\w\.\|+-]+\s?\})|\B%\d+\$[a-zA-Z]+%\B|(?:%[GYIHgyhg]-%[MImi](?:-%[DSAdsa])?)|(?:%[GYIHgyhg]:%[MImi](?::%[DSAdsa])?)|(?:%[DGYIHdgyhg].%[MImi](?:.%[YDSAydsa])?)|(?:%[GYIHgyhg]%[MImi](?:%[DSAdsa])?)|%(?:\d{1,2}\$)?[-+^#0]{0,2}?(?:\d{1'...</font> <i>(length=1519)</i>
  <i>protected</i> 'last_string' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'assets_export' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'as_xliff' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'processorScripts' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'PostprocessCsvToResxScript'</font> <i>(length=26)</i>
  <i>protected</i> 'translationsGroupedBySource' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'user_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>79</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260431  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$file&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'/master2/README.md'</font> <i>(length=18)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$fileName&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$filePath&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$files_parent_id&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$in_xliff&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>boolean</small> <font color='#75507b'>false</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$info&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$language&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>array</b> <i>(size=8)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
  'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
  'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  'plural_ids' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      0 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$lastUpdate&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'2019-04-08 15:56:44'</font> <i>(length=19)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$mimeType&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$pathInfo&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>array</b> <i>(size=4)</i>
  'dirname' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/master2'</font> <i>(length=8)</i>
  'basename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'extension' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md'</font> <i>(length=2)</i>
  'filename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README'</font> <i>(length=6)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
  <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'organization' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'group' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'workflow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
      'parent' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'user' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
      'source_language' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'childs' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'files' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260432  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
  <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
  <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
  <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
  <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
  <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
  <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
  <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
  <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
  <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260434  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260435  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
      <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260436  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
      <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
      <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260437  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project_languages&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>array</b> <i>(size=1)</i>
  0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$requestedEtags&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$source&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>array</b> <i>(size=6)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
  'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
  'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
  'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  'file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$sources&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$translatedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$user&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2426:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'plan' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'info' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      'projects' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'groups' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'notification_channels' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
  <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260438  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
  <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
  <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
  <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
  <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
  <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
  <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
  <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
  <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
  <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
  <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
</table></font>
<br />
<font size='1'><table class='xdebug-error xe-warning' dir='ltr' border='1' cellspacing='0' cellpadding='1'>
<tr><th align='left' bgcolor='#f57900' colspan="5"><span style='background-color: #cc0000; color: #fce94f; font-size: x-large;'>( ! )</span> Warning: Cannot modify header information - headers already sent by (output started at /home/crowdin/valeriy/crowdin-backend/modules/Exporters/ExportFactory.php:837) in /home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php on line <i>2427</i></th></tr>
<tr><th align='left' bgcolor='#e9b96e' colspan='5'>Call Stack</th></tr>
<tr><th align='center' bgcolor='#eeeeec'>#</th><th align='left' bgcolor='#eeeeec'>Time</th><th align='left' bgcolor='#eeeeec'>Memory</th><th align='left' bgcolor='#eeeeec'>Function</th><th align='left' bgcolor='#eeeeec'>Location</th></tr>
<tr><td bgcolor='#eeeeec' align='center'>1</td><td bgcolor='#eeeeec' align='center'>0.0001</td><td bgcolor='#eeeeec' align='right'>360080</td><td bgcolor='#eeeeec'>{main}(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>0</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>2</td><td bgcolor='#eeeeec' align='center'>0.0252</td><td bgcolor='#eeeeec' align='right'>4627624</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Application->run(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>9</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>3</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Application.php' bgcolor='#eeeeec'>.../Application.php<b>:</b>88</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>4</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>147</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>5</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6173856</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->do_export_file(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/Controller.php' bgcolor='#eeeeec'>.../Controller.php<b>:</b>110</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>6</td><td bgcolor='#eeeeec' align='center'>0.6091</td><td bgcolor='#eeeeec' align='right'>16457928</td><td bgcolor='#eeeeec'><a href='http://www.php.net/function.header' target='_new'>header</a>
(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>2427</td></tr>
<tr><th align='left' colspan='5' bgcolor='#e9b96e'>Variables in local scope (#5)</th></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$approvedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$attributes&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>array</b> <i>(size=2)</i>
  'mime_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
  'filesize' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>20</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$e&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$etag&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'af8b063373c53c5eae5c6a088f98b8e2'</font> <i>(length=32)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exception&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exporter&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
  <i>protected</i> 'source' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\source</i>)[<i>72</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'file' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
          'language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'translations' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\translation'</font> <i>(length=34)</i>
      <i>private</i> 'revertInfo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'project' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'parallel_lock_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'is_action_allowed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>79</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260440  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source'</font> <i>(length=6)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
      <i>public</i> 'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
      <i>public</i> 'language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'path' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/13616315/287343/1535.md'</font> <i>(length=24)</i>
      <i>public</i> 'revision' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'parent' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'words_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'scheme' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> '__file' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\file</i>)[<i>73</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'project' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'source' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'sources' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>79</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
          <i>public</i> 'project_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
          <i>public</i> 'draft_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
          <i>public</i> 'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'priority' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
          <i>public</i> 'export_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/folder1/%two_letters_code%/%original_file_name%'</font> <i>(length=48)</i>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:18'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:19'</font> <i>(length=19)</i>
          <i>public</i> 'last_accessed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'title' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> '__project' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>168</i>]
              <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=6)</i>
                  ...
              <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
                  ...
              <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
              <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
              <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
              <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
              <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
              <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
              <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
              <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
              <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
              <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
              <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
              <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
              <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>protected</i> 'target_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>86</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260442  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1030'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'6'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe'</font> <i>(length=6)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'438'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'dan'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da-DK'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project_languages' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>protected</i> 'user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>74</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260443  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
      <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=6)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'group' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'workflow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'source_language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'childs' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'files' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260444  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
      <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
      <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
      <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
      <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
      <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
      <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'info' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'projects' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'groups' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'notification_channels' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
          <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
          <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
          <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
          <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
          <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
          <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
          <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
          <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
          <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
          <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
          <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'user' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'parent' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'organization' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
          <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
          <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
          <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
          <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
          <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
          <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
          <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
          <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
          <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
          <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
          <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
          <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
          <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
          <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
          <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
          <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
          <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
          <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> '_target_directory' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'plurals_mapping' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      5 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
  <i>protected</i> 'max_workflow_step_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'sources' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'export_option_translate_duplicates' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_approved_only' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_translate_dialects' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_suggestions' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      1 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      2 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      3 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_statistic' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'start' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      'end' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730766</font>
  <i>protected</i> 'exporter' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>md14_exporter</i>)[<i>172</i>]
      <i>protected</i> 'marker_tag_li' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'-'</font> <i>(length=1)</i>
      <i>protected</i> 'htmlExporter' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>html11_exporter</i>)[<i>163</i>]
          <i>protected</i> 'sourceFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/importer/13616315/287343/1535.md.html'</font> <i>(length=79)</i>
          <i>protected</i> 'resulted_file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
          <i>protected</i> 'webXmlExport' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> 'parser' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>html11_parser</i>)[<i>216</i>]
              <i>protected</i> 'html_inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=15)</i>
                  ...
              <i>protected</i> 'is_translatable_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/^[%^&amp;*@#~&gt;&lt;|=_+-]+$/'</font> <i>(length=21)</i>
              <i>protected</i> 'inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=24)</i>
                  ...
              <i>protected</i> 'nodeIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>7</font>
              <i>protected</i> 'translationIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>2</font>
              <i>protected</i> 'madCapMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xml2Mode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'webXmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'translateContent' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translateAttributes' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translatableElements' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> 'contentSegmentation' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'html' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>simple_html_dom</i>)[<i>207</i>]
                  ...
              <i>private</i> 'data' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'mask_phrases_in_html' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'segmentation' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\Utils\SrxSegmentation</i>)[<i>120</i>]
                  ...
              <i>private</i> 'export_file' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
              <i>protected</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
                <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
            <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> 'resultedFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
      <i>protected</i> 'iframe_helpers' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'listMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> 'listLineEndingsMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
        <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
      <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'pseudolocalization' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'last_translation' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886300'</font> <i>(length=6)</i>
      'text' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'int_test'</font> <i>(length=8)</i>
      'duplicate_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886299'</font> <i>(length=6)</i>
      'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:8:{s:6:&quot;hidden&quot;;b:0;s:11:&quot;description&quot;;s:14:&quot;Paragraph text&quot;;s:9:&quot;attribute&quot;;b:0;s:4:&quot;path&quot;;s:2:&quot;/p&quot;;s:10:&quot;identifier&quot;;s:32:&quot;b86493d2ae255a02bb7ea61e7fb77c10&quot;;s:8:&quot;rtrimmed&quot;;s:0:&quot;&quot;;s:8:&quot;ltrimmed&quot;;s:0:&quot;&quot;;s:5:&quot;index&quot;;i:5;}'</font> <i>(length=222)</i>
      'context' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Paragraph text&#13;&#10;XPath: /p'</font> <i>(length=25)</i>
      'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'last_translation_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'untranslated'</font> <i>(length=12)</i>
  <i>private</i> 'last_suggestion' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'icu_parser' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'placeholdersRegExp' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/&amp;[a-z_]+&amp;|\B%(?:\d+\$)*#@[^@]+@(?:(?![\p{L}\d])|$)|\{\$\w+\}|\[\/?[%\w\.-]+\]|\B\:[\w\.-]+\:\B|\$[\w\.!+-]+\$|\$\([\w\.-]+\)|\#\{[\w\.\$-]+\}\#?(?!\{)|\$\{[\w\.-]+\}\$?(?![\{\(\[])|\b__\w+__\b|\*\|.*?\|\*|\\\(\w+\)|(?:\{{3}\s?[\w\.\|+-]+\s?\}{3}|\{{2}\s?[\w\.\|+-]+\s?\}{2}|\{\s?[\w\.\|+-]+\s?\})|\B%\d+\$[a-zA-Z]+%\B|(?:%[GYIHgyhg]-%[MImi](?:-%[DSAdsa])?)|(?:%[GYIHgyhg]:%[MImi](?::%[DSAdsa])?)|(?:%[DGYIHdgyhg].%[MImi](?:.%[YDSAydsa])?)|(?:%[GYIHgyhg]%[MImi](?:%[DSAdsa])?)|%(?:\d{1,2}\$)?[-+^#0]{0,2}?(?:\d{1'...</font> <i>(length=1519)</i>
  <i>protected</i> 'last_string' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'assets_export' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'as_xliff' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'processorScripts' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'PostprocessCsvToResxScript'</font> <i>(length=26)</i>
  <i>protected</i> 'translationsGroupedBySource' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'user_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>79</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260451  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$file&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'/master2/README.md'</font> <i>(length=18)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$fileName&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$filePath&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$files_parent_id&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$in_xliff&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>boolean</small> <font color='#75507b'>false</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$info&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$language&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>array</b> <i>(size=8)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
  'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
  'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  'plural_ids' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      0 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$lastUpdate&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'2019-04-08 15:56:44'</font> <i>(length=19)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$mimeType&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$pathInfo&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>array</b> <i>(size=4)</i>
  'dirname' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/master2'</font> <i>(length=8)</i>
  'basename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'extension' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md'</font> <i>(length=2)</i>
  'filename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README'</font> <i>(length=6)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
  <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'organization' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'group' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'workflow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
      'parent' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'user' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
      'source_language' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'childs' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'files' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260452  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
  <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
  <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
  <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
  <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
  <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
  <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
  <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
  <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
  <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260454  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260455  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
      <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260456  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
      <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
      <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260457  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project_languages&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>array</b> <i>(size=1)</i>
  0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$requestedEtags&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$source&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>array</b> <i>(size=6)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
  'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
  'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
  'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  'file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$sources&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$translatedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$user&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2427:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'plan' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'info' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      'projects' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'groups' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'notification_channels' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
  <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260458  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
  <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
  <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
  <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
  <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
  <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
  <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
  <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
  <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
  <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
  <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
</table></font>
<br />
<font size='1'><table class='xdebug-error xe-warning' dir='ltr' border='1' cellspacing='0' cellpadding='1'>
<tr><th align='left' bgcolor='#f57900' colspan="5"><span style='background-color: #cc0000; color: #fce94f; font-size: x-large;'>( ! )</span> Warning: Cannot modify header information - headers already sent by (output started at /home/crowdin/valeriy/crowdin-backend/modules/Exporters/ExportFactory.php:837) in /home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php on line <i>2428</i></th></tr>
<tr><th align='left' bgcolor='#e9b96e' colspan='5'>Call Stack</th></tr>
<tr><th align='center' bgcolor='#eeeeec'>#</th><th align='left' bgcolor='#eeeeec'>Time</th><th align='left' bgcolor='#eeeeec'>Memory</th><th align='left' bgcolor='#eeeeec'>Function</th><th align='left' bgcolor='#eeeeec'>Location</th></tr>
<tr><td bgcolor='#eeeeec' align='center'>1</td><td bgcolor='#eeeeec' align='center'>0.0001</td><td bgcolor='#eeeeec' align='right'>360080</td><td bgcolor='#eeeeec'>{main}(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>0</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>2</td><td bgcolor='#eeeeec' align='center'>0.0252</td><td bgcolor='#eeeeec' align='right'>4627624</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Application->run(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>9</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>3</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Application.php' bgcolor='#eeeeec'>.../Application.php<b>:</b>88</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>4</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>147</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>5</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6173856</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->do_export_file(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/Controller.php' bgcolor='#eeeeec'>.../Controller.php<b>:</b>110</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>6</td><td bgcolor='#eeeeec' align='center'>0.6238</td><td bgcolor='#eeeeec' align='right'>16457688</td><td bgcolor='#eeeeec'><a href='http://www.php.net/function.header' target='_new'>header</a>
(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>2428</td></tr>
<tr><th align='left' colspan='5' bgcolor='#e9b96e'>Variables in local scope (#5)</th></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$approvedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$attributes&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>array</b> <i>(size=2)</i>
  'mime_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
  'filesize' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>20</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$e&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$etag&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'af8b063373c53c5eae5c6a088f98b8e2'</font> <i>(length=32)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exception&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exporter&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
  <i>protected</i> 'source' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\source</i>)[<i>72</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'file' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
          'language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'translations' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\translation'</font> <i>(length=34)</i>
      <i>private</i> 'revertInfo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'project' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'parallel_lock_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'is_action_allowed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>79</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260459  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source'</font> <i>(length=6)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
      <i>public</i> 'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
      <i>public</i> 'language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'path' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/13616315/287343/1535.md'</font> <i>(length=24)</i>
      <i>public</i> 'revision' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'parent' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'words_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'scheme' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> '__file' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\file</i>)[<i>73</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'project' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'source' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'sources' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>79</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
          <i>public</i> 'project_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
          <i>public</i> 'draft_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
          <i>public</i> 'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'priority' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
          <i>public</i> 'export_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/folder1/%two_letters_code%/%original_file_name%'</font> <i>(length=48)</i>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:18'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:19'</font> <i>(length=19)</i>
          <i>public</i> 'last_accessed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'title' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> '__project' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>168</i>]
              <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=6)</i>
                  ...
              <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
                  ...
              <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
              <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
              <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
              <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
              <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
              <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
              <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
              <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
              <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
              <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
              <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
              <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
              <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>protected</i> 'target_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>86</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260461  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1030'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'6'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe'</font> <i>(length=6)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'438'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'dan'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da-DK'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project_languages' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>protected</i> 'user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>74</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260462  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
      <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=6)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'group' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'workflow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'source_language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'childs' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'files' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260463  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
      <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
      <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
      <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
      <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
      <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
      <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'info' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'projects' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'groups' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'notification_channels' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
          <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
          <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
          <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
          <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
          <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
          <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
          <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
          <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
          <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
          <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
          <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'user' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'parent' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'organization' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
          <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
          <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
          <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
          <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
          <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
          <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
          <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
          <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
          <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
          <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
          <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
          <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
          <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
          <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
          <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
          <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
          <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
          <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> '_target_directory' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'plurals_mapping' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      5 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
  <i>protected</i> 'max_workflow_step_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'sources' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'export_option_translate_duplicates' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_approved_only' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_translate_dialects' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_suggestions' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      1 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      2 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      3 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_statistic' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'start' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      'end' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730766</font>
  <i>protected</i> 'exporter' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>md14_exporter</i>)[<i>172</i>]
      <i>protected</i> 'marker_tag_li' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'-'</font> <i>(length=1)</i>
      <i>protected</i> 'htmlExporter' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>html11_exporter</i>)[<i>163</i>]
          <i>protected</i> 'sourceFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/importer/13616315/287343/1535.md.html'</font> <i>(length=79)</i>
          <i>protected</i> 'resulted_file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
          <i>protected</i> 'webXmlExport' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> 'parser' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>html11_parser</i>)[<i>216</i>]
              <i>protected</i> 'html_inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=15)</i>
                  ...
              <i>protected</i> 'is_translatable_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/^[%^&amp;*@#~&gt;&lt;|=_+-]+$/'</font> <i>(length=21)</i>
              <i>protected</i> 'inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=24)</i>
                  ...
              <i>protected</i> 'nodeIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>7</font>
              <i>protected</i> 'translationIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>2</font>
              <i>protected</i> 'madCapMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xml2Mode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'webXmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'translateContent' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translateAttributes' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translatableElements' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> 'contentSegmentation' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'html' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>simple_html_dom</i>)[<i>207</i>]
                  ...
              <i>private</i> 'data' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'mask_phrases_in_html' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'segmentation' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\Utils\SrxSegmentation</i>)[<i>120</i>]
                  ...
              <i>private</i> 'export_file' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
              <i>protected</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
                <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
            <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> 'resultedFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
      <i>protected</i> 'iframe_helpers' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'listMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> 'listLineEndingsMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
        <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
      <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'pseudolocalization' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'last_translation' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886300'</font> <i>(length=6)</i>
      'text' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'int_test'</font> <i>(length=8)</i>
      'duplicate_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886299'</font> <i>(length=6)</i>
      'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:8:{s:6:&quot;hidden&quot;;b:0;s:11:&quot;description&quot;;s:14:&quot;Paragraph text&quot;;s:9:&quot;attribute&quot;;b:0;s:4:&quot;path&quot;;s:2:&quot;/p&quot;;s:10:&quot;identifier&quot;;s:32:&quot;b86493d2ae255a02bb7ea61e7fb77c10&quot;;s:8:&quot;rtrimmed&quot;;s:0:&quot;&quot;;s:8:&quot;ltrimmed&quot;;s:0:&quot;&quot;;s:5:&quot;index&quot;;i:5;}'</font> <i>(length=222)</i>
      'context' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Paragraph text&#13;&#10;XPath: /p'</font> <i>(length=25)</i>
      'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'last_translation_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'untranslated'</font> <i>(length=12)</i>
  <i>private</i> 'last_suggestion' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'icu_parser' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'placeholdersRegExp' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/&amp;[a-z_]+&amp;|\B%(?:\d+\$)*#@[^@]+@(?:(?![\p{L}\d])|$)|\{\$\w+\}|\[\/?[%\w\.-]+\]|\B\:[\w\.-]+\:\B|\$[\w\.!+-]+\$|\$\([\w\.-]+\)|\#\{[\w\.\$-]+\}\#?(?!\{)|\$\{[\w\.-]+\}\$?(?![\{\(\[])|\b__\w+__\b|\*\|.*?\|\*|\\\(\w+\)|(?:\{{3}\s?[\w\.\|+-]+\s?\}{3}|\{{2}\s?[\w\.\|+-]+\s?\}{2}|\{\s?[\w\.\|+-]+\s?\})|\B%\d+\$[a-zA-Z]+%\B|(?:%[GYIHgyhg]-%[MImi](?:-%[DSAdsa])?)|(?:%[GYIHgyhg]:%[MImi](?::%[DSAdsa])?)|(?:%[DGYIHdgyhg].%[MImi](?:.%[YDSAydsa])?)|(?:%[GYIHgyhg]%[MImi](?:%[DSAdsa])?)|%(?:\d{1,2}\$)?[-+^#0]{0,2}?(?:\d{1'...</font> <i>(length=1519)</i>
  <i>protected</i> 'last_string' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'assets_export' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'as_xliff' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'processorScripts' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'PostprocessCsvToResxScript'</font> <i>(length=26)</i>
  <i>protected</i> 'translationsGroupedBySource' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'user_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>79</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260468  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$file&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'/master2/README.md'</font> <i>(length=18)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$fileName&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$filePath&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$files_parent_id&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$in_xliff&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>boolean</small> <font color='#75507b'>false</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$info&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$language&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>array</b> <i>(size=8)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
  'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
  'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  'plural_ids' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      0 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$lastUpdate&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'2019-04-08 15:56:44'</font> <i>(length=19)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$mimeType&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$pathInfo&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>array</b> <i>(size=4)</i>
  'dirname' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/master2'</font> <i>(length=8)</i>
  'basename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'extension' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md'</font> <i>(length=2)</i>
  'filename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README'</font> <i>(length=6)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
  <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'organization' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'group' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'workflow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
      'parent' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'user' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
      'source_language' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'childs' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'files' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260469  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
  <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
  <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
  <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
  <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
  <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
  <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
  <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
  <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
  <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260470  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260471  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
      <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260472  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
      <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
      <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260473  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project_languages&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>array</b> <i>(size=1)</i>
  0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$requestedEtags&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$source&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>array</b> <i>(size=6)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
  'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
  'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
  'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  'file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$sources&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$translatedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$user&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2428:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'plan' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'info' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      'projects' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'groups' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'notification_channels' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
  <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260474  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
  <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
  <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
  <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
  <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
  <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
  <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
  <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
  <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
  <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
  <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
</table></font>
<br />
<font size='1'><table class='xdebug-error xe-warning' dir='ltr' border='1' cellspacing='0' cellpadding='1'>
<tr><th align='left' bgcolor='#f57900' colspan="5"><span style='background-color: #cc0000; color: #fce94f; font-size: x-large;'>( ! )</span> Warning: Cannot modify header information - headers already sent by (output started at /home/crowdin/valeriy/crowdin-backend/modules/Exporters/ExportFactory.php:837) in /home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php on line <i>2429</i></th></tr>
<tr><th align='left' bgcolor='#e9b96e' colspan='5'>Call Stack</th></tr>
<tr><th align='center' bgcolor='#eeeeec'>#</th><th align='left' bgcolor='#eeeeec'>Time</th><th align='left' bgcolor='#eeeeec'>Memory</th><th align='left' bgcolor='#eeeeec'>Function</th><th align='left' bgcolor='#eeeeec'>Location</th></tr>
<tr><td bgcolor='#eeeeec' align='center'>1</td><td bgcolor='#eeeeec' align='center'>0.0001</td><td bgcolor='#eeeeec' align='right'>360080</td><td bgcolor='#eeeeec'>{main}(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>0</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>2</td><td bgcolor='#eeeeec' align='center'>0.0252</td><td bgcolor='#eeeeec' align='right'>4627624</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Application->run(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/www/index.php' bgcolor='#eeeeec'>.../index.php<b>:</b>9</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>3</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Application.php' bgcolor='#eeeeec'>.../Application.php<b>:</b>88</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>4</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6108280</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->performAction(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>147</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>5</td><td bgcolor='#eeeeec' align='center'>0.0312</td><td bgcolor='#eeeeec' align='right'>6173856</td><td bgcolor='#eeeeec'>Crowdin\App\MVC\Controllers\api_controller->do_export_file(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/Controller.php' bgcolor='#eeeeec'>.../Controller.php<b>:</b>110</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>6</td><td bgcolor='#eeeeec' align='center'>0.6293</td><td bgcolor='#eeeeec' align='right'>16457672</td><td bgcolor='#eeeeec'><a href='http://www.php.net/function.header' target='_new'>header</a>
(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php' bgcolor='#eeeeec'>.../api_controller.php<b>:</b>2429</td></tr>
<tr><th align='left' colspan='5' bgcolor='#e9b96e'>Variables in local scope (#5)</th></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$approvedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$attributes&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>array</b> <i>(size=2)</i>
  'mime_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
  'filesize' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>20</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$e&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$etag&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'af8b063373c53c5eae5c6a088f98b8e2'</font> <i>(length=32)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exception&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$exporter&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
  <i>protected</i> 'source' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\source</i>)[<i>72</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'file' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
          'language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'translations' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\translation'</font> <i>(length=34)</i>
      <i>private</i> 'revertInfo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'project' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'parallel_lock_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'is_action_allowed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>79</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260475  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source'</font> <i>(length=6)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
      <i>public</i> 'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
      <i>public</i> 'language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'path' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/13616315/287343/1535.md'</font> <i>(length=24)</i>
      <i>public</i> 'revision' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'parent' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'words_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'scheme' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> '__file' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\file</i>)[<i>73</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'project' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'source' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'sources' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>79</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'file'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
          <i>public</i> 'project_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
          <i>public</i> 'draft_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
          <i>public</i> 'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'priority' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
          <i>public</i> 'export_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/folder1/%two_letters_code%/%original_file_name%'</font> <i>(length=48)</i>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:18'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:53:19'</font> <i>(length=19)</i>
          <i>public</i> 'last_accessed' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'title' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> '__project' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>168</i>]
              <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=6)</i>
                  ...
              <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
                  ...
              <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
              <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
              <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
              <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
              <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
              <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
              <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
              <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
              <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
              <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
              <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
              <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
              <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
              <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
              <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
              <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
              <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
              <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>protected</i> 'target_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>86</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260477  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1030'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'6'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe'</font> <i>(length=6)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'438'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'dan'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da-DK'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project_languages' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>protected</i> 'user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>74</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260478  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'project' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
      <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=6)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'group' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'workflow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'source_language' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'childs' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'files' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260479  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
      <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
      <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
      <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
      <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
      <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
      <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
              'info' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'projects' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'groups' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'notification_channels' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
          <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
          <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
          <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
          <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
          <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
          <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
          <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
          <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
          <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
          <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
          <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
          <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
          <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'user' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'parent' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
              'organization' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=3)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
          <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
          <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              'plan' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=2)</i>
                  ...
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
          <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
          <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
          <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
          <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
          <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
          <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
          <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
          <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=1)</i>
              0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
          <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
              <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>mysqli</i>)[<i>30</i>]
                  ...
              <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
              <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=5)</i>
                  ...
              <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
          <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
          <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
          <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
          <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
          <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
          <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
          <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
          <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
          <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
          <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
          <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
          <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
          <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
          <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
          <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
          <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
          <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
          <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
          <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> '_target_directory' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'plurals_mapping' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      5 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
  <i>protected</i> 'max_workflow_step_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'sources' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'export_option_translate_duplicates' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_approved_only' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_option_translate_dialects' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'export_suggestions' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      1 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      2 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      3 <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_statistic' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'start' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      'end' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730766</font>
  <i>protected</i> 'exporter' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>md14_exporter</i>)[<i>172</i>]
      <i>protected</i> 'marker_tag_li' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'-'</font> <i>(length=1)</i>
      <i>protected</i> 'htmlExporter' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>html11_exporter</i>)[<i>163</i>]
          <i>protected</i> 'sourceFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/importer/13616315/287343/1535.md.html'</font> <i>(length=79)</i>
          <i>protected</i> 'resulted_file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
          <i>protected</i> 'webXmlExport' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>protected</i> 'parser' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>html11_parser</i>)[<i>216</i>]
              <i>protected</i> 'html_inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=15)</i>
                  ...
              <i>protected</i> 'is_translatable_pattern' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/^[%^&amp;*@#~&gt;&lt;|=_+-]+$/'</font> <i>(length=21)</i>
              <i>protected</i> 'inline_tags' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=24)</i>
                  ...
              <i>protected</i> 'nodeIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>7</font>
              <i>protected</i> 'translationIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>2</font>
              <i>protected</i> 'madCapMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'xml2Mode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'webXmlMode' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>protected</i> 'translateContent' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translateAttributes' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'translatableElements' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>protected</i> 'contentSegmentation' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
              <i>protected</i> 'html' <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>simple_html_dom</i>)[<i>207</i>]
                  ...
              <i>private</i> 'data' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>private</i> 'mask_phrases_in_html' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
              <i>private</i> 'segmentation' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> 
                <b>object</b>(<i>Crowdin\App\Src\Utils\SrxSegmentation</i>)[<i>120</i>]
                  ...
              <i>private</i> 'export_file' <small>(html_parser)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
              <i>protected</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
                <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
            <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
          <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> 'resultedFileName' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
      <i>protected</i> 'iframe_helpers' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'listMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> 'listLineEndingsMasks' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>public</i> 'export_factory' <font color='#888a85'>=&gt;</font> 
        <i>&amp;</i><b>object</b>(<i>Crowdin\App\Modules\Exporters\ExportFactory</i>)[<i>66</i>]
      <i>protected</i> 'index' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> 'pseudolocalization' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'last_translation' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886300'</font> <i>(length=6)</i>
      'text' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'int_test'</font> <i>(length=8)</i>
      'duplicate_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'886299'</font> <i>(length=6)</i>
      'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:8:{s:6:&quot;hidden&quot;;b:0;s:11:&quot;description&quot;;s:14:&quot;Paragraph text&quot;;s:9:&quot;attribute&quot;;b:0;s:4:&quot;path&quot;;s:2:&quot;/p&quot;;s:10:&quot;identifier&quot;;s:32:&quot;b86493d2ae255a02bb7ea61e7fb77c10&quot;;s:8:&quot;rtrimmed&quot;;s:0:&quot;&quot;;s:8:&quot;ltrimmed&quot;;s:0:&quot;&quot;;s:5:&quot;index&quot;;i:5;}'</font> <i>(length=222)</i>
      'context' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Paragraph text&#13;&#10;XPath: /p'</font> <i>(length=25)</i>
      'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>protected</i> 'last_translation_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'untranslated'</font> <i>(length=12)</i>
  <i>private</i> 'last_suggestion' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>private</i> 'icu_parser' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'placeholdersRegExp' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/&amp;[a-z_]+&amp;|\B%(?:\d+\$)*#@[^@]+@(?:(?![\p{L}\d])|$)|\{\$\w+\}|\[\/?[%\w\.-]+\]|\B\:[\w\.-]+\:\B|\$[\w\.!+-]+\$|\$\([\w\.-]+\)|\#\{[\w\.\$-]+\}\#?(?!\{)|\$\{[\w\.-]+\}\$?(?![\{\(\[])|\b__\w+__\b|\*\|.*?\|\*|\\\(\w+\)|(?:\{{3}\s?[\w\.\|+-]+\s?\}{3}|\{{2}\s?[\w\.\|+-]+\s?\}{2}|\{\s?[\w\.\|+-]+\s?\})|\B%\d+\$[a-zA-Z]+%\B|(?:%[GYIHgyhg]-%[MImi](?:-%[DSAdsa])?)|(?:%[GYIHgyhg]:%[MImi](?::%[DSAdsa])?)|(?:%[DGYIHdgyhg].%[MImi](?:.%[YDSAydsa])?)|(?:%[GYIHgyhg]%[MImi](?:%[DSAdsa])?)|%(?:\d{1,2}\$)?[-+^#0]{0,2}?(?:\d{1'...</font> <i>(length=1519)</i>
  <i>protected</i> 'last_string' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'assets_export' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'as_xliff' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> 'processorScripts' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=1)</i>
      0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'PostprocessCsvToResxScript'</font> <i>(length=26)</i>
  <i>protected</i> 'translationsGroupedBySource' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> 'user_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>39</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>79</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>3615</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260484  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980913</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin_13616315'</font> <i>(length=16)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$file&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'/master2/README.md'</font> <i>(length=18)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$fileName&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$filePath&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'/home/crowdin/valeriy/crowdin-backend/var/tmp/exporter/287343/da/1828_1:1_README.md'</font> <i>(length=83)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$files_parent_id&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'1825'</font> <i>(length=4)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$in_xliff&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>boolean</small> <font color='#75507b'>false</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$info&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$language&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>array</b> <i>(size=8)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
  'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Danish'</font> <i>(length=6)</i>
  'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'da'</font> <i>(length=2)</i>
  'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  'plural_ids' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      0 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
      1 <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>5</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$lastUpdate&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'2019-04-08 15:56:44'</font> <i>(length=19)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$mimeType&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><small>string</small> <font color='#cc0000'>'text/plain'</font> <i>(length=10)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$pathInfo&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>array</b> <i>(size=4)</i>
  'dirname' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'/master2'</font> <i>(length=8)</i>
  'basename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'extension' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md'</font> <i>(length=2)</i>
  'filename' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README'</font> <i>(length=6)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\project</i>)[<i>33</i>]
  <i>private</i> '_managers' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'projectWorkflowSteps' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_db' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_tm_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_default_glossary_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'workflowData' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> 'clientExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>private</i> 'vendorExternalProject' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=6)</i>
      'organization' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'group' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group_id'</font> <i>(length=8)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'workflow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'workflow_id'</font> <i>(length=11)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\workflow'</font> <i>(length=31)</i>
      'parent' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'user' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
      'source_language' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'source_language_id'</font> <i>(length=18)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\language'</font> <i>(length=31)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'childs' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'files' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project_id'</font> <i>(length=10)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\file'</font> <i>(length=27)</i>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260485  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'project'</font> <i>(length=7)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'287343'</font> <i>(length=6)</i>
  <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'group_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
  <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'source_language_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
  <i>public</i> 'target_languages' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 10:45:53'</font> <i>(length=19)</i>
  <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'resx2csv'</font> <i>(length=8)</i>
  <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'social_buttons' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'join_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'private'</font> <i>(length=7)</i>
  <i>public</i> 'multi_factor_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'language_access_policy' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'open'</font> <i>(length=4)</i>
  <i>public</i> 'glossary_access' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'last_build' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_activity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 15:54:11'</font> <i>(length=19)</i>
  <i>public</i> 'downloadable' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'allow_remote_translation' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'widget_status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'jipt_language_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'jipt_project_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'export_options' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2259ab241ac10f08d212db397a5ef1e3'</font> <i>(length=32)</i>
  <i>public</i> 'invitation_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'7ad1840e214ee8fd3f5b0e7b555f4c6f'</font> <i>(length=32)</i>
  <i>public</i> 'show_ads' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'is_mt_allowed' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_suggestions' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'autoapprove_measure' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'auto_substitution' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'use_global_tm' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'full_rebuild' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'featured' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'notify_options' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'qa_settings' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;is_active&quot;:1,&quot;categories&quot;:{&quot;1&quot;:1,&quot;7&quot;:1,&quot;3&quot;:1,&quot;6&quot;:1,&quot;2&quot;:1,&quot;4&quot;:1,&quot;5&quot;:1,&quot;8&quot;:1,&quot;9&quot;:1,&quot;10&quot;:1,&quot;11&quot;:1}}'</font> <i>(length=98)</i>
  <i>public</i> 'web_hook' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'external_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'advanced_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'total_phrases' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
  <i>public</i> 'total_members' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> '__user' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
          'info' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'projects' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
          'groups' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'notification_channels' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
      <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260486  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
      <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
      <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
      <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
      <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
      <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
      <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
      <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
      <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
      <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
      <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
      <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
      <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
      <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> '__group' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\group</i>)[<i>76</i>]
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'user' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user'</font> <i>(length=27)</i>
          'parent' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'parent_id'</font> <i>(length=9)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
          'organization' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=3)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization_id'</font> <i>(length=15)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\organization'</font> <i>(length=35)</i>
              'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260487  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'group'</font> <i>(length=5)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'76979'</font> <i>(length=5)</i>
      <i>public</i> 'identifier' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'visibility' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'parent_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'user_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__organization' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\organization</i>)[<i>77</i>]
      <i>private</i> 'owner' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          'plan' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=2)</i>
              'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
              'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260488  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'organization'</font> <i>(length=12)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'domain' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'owner_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
      <i>public</i> 'plan_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2851501'</font> <i>(length=7)</i>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'description' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
      <i>public</i> 'logo' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'background' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin_13616315&quot;}'</font> <i>(length=54)</i>
      <i>public</i> 'tm_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;local.tm&quot;}'</font> <i>(length=19)</i>
      <i>public</i> 'namespace_dsn' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'{&quot;host&quot;:&quot;192.168.1.203&quot;,&quot;database&quot;:&quot;crowdin&quot;}'</font> <i>(length=45)</i>
      <i>public</i> 'created_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:57'</font> <i>(length=19)</i>
      <i>public</i> 'updated_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:14:59'</font> <i>(length=19)</i>
  <i>public</i> '__source_language' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\MVC\Models\language</i>)[<i>67</i>]
      <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>86400</font>
      <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=1)</i>
          0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'name'</font> <i>(length=4)</i>
      <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
          <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
            <b>object</b>(<i>mysqli</i>)[<i>30</i>]
              <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
              <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
              <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
              <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
              <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
                <b>array</b> <i>(size=0)</i>
                  ...
              <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
              <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
              <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
              <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
              <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
              <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
              <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260489  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
              <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
              <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
              <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
              <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
          <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=5)</i>
              'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
              'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
              'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
              'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
          <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'language'</font> <i>(length=8)</i>
      <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'58'</font> <i>(length=2)</i>
      <i>public</i> 'organization_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'English'</font> <i>(length=7)</i>
      <i>public</i> 'code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'internal_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'encoding' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'UTF-8'</font> <i>(length=5)</i>
      <i>public</i> 'text_direction' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'ltr'</font> <i>(length=3)</i>
      <i>public</i> 'special_characters' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>public</i> 'plural_category_names' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:3:&quot;one&quot;;i:1;s:5:&quot;other&quot;;}'</font> <i>(length=36)</i>
      <i>public</i> 'plural_examples' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{i:0;s:1:&quot;1&quot;;i:1;s:22:&quot;0, 2-999; 1.2, 2.07...&quot;;}'</font> <i>(length=52)</i>
      <i>public</i> 'plural_rules' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'(n != 1)'</font> <i>(length=8)</i>
      <i>public</i> 'plural_forms_count' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2'</font> <i>(length=1)</i>
      <i>public</i> 'windows_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1033'</font> <i>(length=4)</i>
      <i>public</i> 'symbian_locale_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
      <i>public</i> 'microsoft_culture_identifier' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9'</font> <i>(length=1)</i>
      <i>public</i> 'region' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'America'</font> <i>(length=7)</i>
      <i>public</i> 'popularity' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'783'</font> <i>(length=3)</i>
      <i>public</i> 'two_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en'</font> <i>(length=2)</i>
      <i>public</i> 'three_letters_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'eng'</font> <i>(length=3)</i>
      <i>public</i> 'locale_code' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'en-US'</font> <i>(length=5)</i>
      <i>public</i> 'pragma_codepage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1252'</font> <i>(length=4)</i>
      <i>public</i> 'dialect_of' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$project_languages&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>array</b> <i>(size=1)</i>
  0 <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'10'</font> <i>(length=2)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$requestedEtags&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$source&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>array</b> <i>(size=6)</i>
  'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1535'</font> <i>(length=4)</i>
  'file_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1828'</font> <i>(length=4)</i>
  'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'md14'</font> <i>(length=4)</i>
  'node_type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  'file_name' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'README.md'</font> <i>(length=9)</i>
  'attributes' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'a:2:{s:9:&quot;mime_type&quot;;s:10:&quot;text/plain&quot;;s:8:&quot;filesize&quot;;i:20;}'</font> <i>(length=60)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$sources&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$translatedOnly&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small><font color='#3465a4'>null</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$user&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/mvc/Controllers/api_controller.php:2429:</small>
<b>object</b>(<i>Crowdin\App\MVC\Models\user</i>)[<i>34</i>]
  <i>protected</i> '_hasOne' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'plan' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=3)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'plan_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\plan'</font> <i>(length=27)</i>
          'general_db' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
      'info' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'info_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\user_info'</font> <i>(length=32)</i>
  <i>protected</i> '_hasMany' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=3)</i>
      'projects' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\project'</font> <i>(length=30)</i>
      'groups' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\group'</font> <i>(length=28)</i>
      'notification_channels' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=2)</i>
          'field' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user_id'</font> <i>(length=7)</i>
          'class' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Crowdin\App\MVC\Models\notification_channel'</font> <i>(length=43)</i>
  <i>protected</i> '_password' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_is_logged_in' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>true</font>
  <i>protected</i> '_role' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_user_settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>protected</i> '_db' <font color='#888a85'>=&gt;</font> 
    <b>object</b>(<i>Crowdin\App\Src\DatabaseGateway\DatabaseGateway</i>)[<i>29</i>]
      <i>private</i> 'connectionId' <font color='#888a85'>=&gt;</font> 
        <b>object</b>(<i>mysqli</i>)[<i>30</i>]
          <i>public</i> 'affected_rows' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
          <i>public</i> 'client_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'mysqlnd 5.0.12-dev - 20150407 - $Id: b5c5906d452ec590732a93b051f3827e02749b83 $'</font> <i>(length=79)</i>
          <i>public</i> 'client_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50012</font>
          <i>public</i> 'connect_errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'connect_error' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'errno' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'error' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
          <i>public</i> 'error_list' <font color='#888a85'>=&gt;</font> 
            <b>array</b> <i>(size=0)</i>
              <i><font color='#888a85'>empty</font></i>
          <i>public</i> 'field_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1</font>
          <i>public</i> 'host_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203 via TCP/IP'</font> <i>(length=24)</i>
          <i>public</i> 'info' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
          <i>public</i> 'insert_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
          <i>public</i> 'server_info' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'5.6.25-log'</font> <i>(length=10)</i>
          <i>public</i> 'server_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>50625</font>
          <i>public</i> 'stat' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Uptime: 1035075  Threads: 5  Questions: 53260490  Slow queries: 36  Opens: 336890  Flush tables: 1  Open tables: 5000  Queries per second avg: 51.455'</font> <i>(length=149)</i>
          <i>public</i> 'sqlstate' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'00000'</font> <i>(length=5)</i>
          <i>public</i> 'protocol_version' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>10</font>
          <i>public</i> 'thread_id' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>980911</font>
          <i>public</i> 'warning_count' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'connectedAt' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>1554730765</font>
      <i>private</i> 'config' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=5)</i>
          'host' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'192.168.1.203'</font> <i>(length=13)</i>
          'user' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'superpuper'</font> <i>(length=10)</i>
          'database' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'crowdin'</font> <i>(length=7)</i>
          'port' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
      <i>private</i> 'lastErrorCode' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'lastErrorMessage' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
      <i>private</i> 'retryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      <i>private</i> 'isTransaction' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
      <i>private</i> 'transactionQueries' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
      <i>private</i> 'currentQueryIndex' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>-1</font>
      <i>private</i> 'handledErrors' <font color='#888a85'>=&gt;</font> 
        <b>array</b> <i>(size=0)</i>
          <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_cacheTTL' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
  <i>protected</i> '_isNew' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  <i>protected</i> '_localizedFields' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>protected</i> '_localizedRow' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=0)</i>
      <i><font color='#888a85'>empty</font></i>
  <i>private</i> '_dbTableName' <small>(Crowdin\App\Src\ActiveRecord\ActiveRecord)</small> <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'user'</font> <i>(length=4)</i>
  <i>public</i> 'id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'13616315'</font> <i>(length=8)</i>
  <i>public</i> 'login' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt15'</font> <i>(length=4)</i>
  <i>public</i> 'hashed_password' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'$2y$10$QZHEm1pPlIcv63gsmV/tC.0azqk4zVP.I.irIh2QlDawcP7WFk7B6'</font> <i>(length=60)</i>
  <i>public</i> 'email' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'vt+15@crowdin.com'</font> <i>(length=17)</i>
  <i>public</i> 'type' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'timezone' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Europe/Kiev'</font> <i>(length=11)</i>
  <i>public</i> 'time_format' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'locale' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'email_verified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'email_exists' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'settings' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'created' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'modified' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-03 15:13:57'</font> <i>(length=19)</i>
  <i>public</i> 'projects_rating' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'last_seen' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-08 12:39:09'</font> <i>(length=19)</i>
  <i>public</i> 'pending_to_remove' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'terms_accepted_at' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'2019-04-05 18:46:52'</font> <i>(length=19)</i>
  <i>public</i> 'settings_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'328999'</font> <i>(length=6)</i>
  <i>public</i> 'info_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'329082'</font> <i>(length=6)</i>
  <i>public</i> 'api_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'c00d4169d921962a0f091b06f9fb8409'</font> <i>(length=32)</i>
  <i>public</i> 'multi_factor_auth_secret' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'multi_factor_enabled_at' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'multi_factor_recovery_key' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'[&quot;01e5319df0c9782a&quot;,&quot;df3d0327d1d2372a&quot;,&quot;696424a57ca4ed27&quot;,&quot;fc4151b28ead75cf&quot;,&quot;093ed34f39d73755&quot;,&quot;365f5987dfffd085&quot;]'</font> <i>(length=115)</i>
  <i>public</i> 'custom_sso_enabled' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'custom_sso_provider_name' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'yandex_translate_api_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_customer_id' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'oht_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_public_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'gengo_secret_key' <font color='#888a85'>=&gt;</font> <font color='#3465a4'>null</font>
  <i>public</i> 'use_features' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'default_workflow_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_tms' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'share_glossaries' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'company_id' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'53642'</font> <i>(length=5)</i>
  <i>public</i> 'company_position' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>''</font> <i>(length=0)</i>
  <i>public</i> 'session_hash' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'9996181530cacd3e13c1d0bf9f852e9f'</font> <i>(length=32)</i>
  <i>public</i> 'show_lead' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'1'</font> <i>(length=1)</i>
  <i>public</i> 'private_profile' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
  <i>public</i> 'status' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'0'</font> <i>(length=1)</i>
</pre></td></tr>
</table></font>
# int_test

int_test<br />
<font size='1'><table class='xdebug-error xe-warning' dir='ltr' border='1' cellspacing='0' cellpadding='1'>
<tr><th align='left' bgcolor='#f57900' colspan="5"><span style='background-color: #cc0000; color: #fce94f; font-size: x-large;'>( ! )</span> Warning: Cannot modify header information - headers already sent by (output started at /home/crowdin/valeriy/crowdin-backend/modules/Exporters/ExportFactory.php:837) in /home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php on line <i>453</i></th></tr>
<tr><th align='left' bgcolor='#e9b96e' colspan='5'>Call Stack</th></tr>
<tr><th align='center' bgcolor='#eeeeec'>#</th><th align='left' bgcolor='#eeeeec'>Time</th><th align='left' bgcolor='#eeeeec'>Memory</th><th align='left' bgcolor='#eeeeec'>Function</th><th align='left' bgcolor='#eeeeec'>Location</th></tr>
<tr><td bgcolor='#eeeeec' align='center'>1</td><td bgcolor='#eeeeec' align='center'>0.6349</td><td bgcolor='#eeeeec' align='right'>16449832</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Core\ErrorHandler->handleFatalError(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>0</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>2</td><td bgcolor='#eeeeec' align='center'>0.6363</td><td bgcolor='#eeeeec' align='right'>16455104</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Core\ErrorHandler->handleApiFatalError(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>50</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>3</td><td bgcolor='#eeeeec' align='center'>0.6364</td><td bgcolor='#eeeeec' align='right'>16455104</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Core\ErrorHandler->showApiError(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>68</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>4</td><td bgcolor='#eeeeec' align='center'>0.6364</td><td bgcolor='#eeeeec' align='right'>16455160</td><td bgcolor='#eeeeec'><a href='http://www.php.net/function.header' target='_new'>header</a>
(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>453</td></tr>
<tr><th align='left' colspan='5' bgcolor='#e9b96e'>Variables in local scope (#3)</th></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$code&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:453:</small><small>int</small> <font color='#4e9a06'>0</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$json_output&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:453:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$message&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:453:</small><small>string</small> <font color='#cc0000'>'Unknown internal error'</font> <i>(length=22)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$output&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:453:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$xmlOutput&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:453:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
</table></font>
<br />
<font size='1'><table class='xdebug-error xe-warning' dir='ltr' border='1' cellspacing='0' cellpadding='1'>
<tr><th align='left' bgcolor='#f57900' colspan="5"><span style='background-color: #cc0000; color: #fce94f; font-size: x-large;'>( ! )</span> Warning: Cannot modify header information - headers already sent by (output started at /home/crowdin/valeriy/crowdin-backend/modules/Exporters/ExportFactory.php:837) in /home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php on line <i>484</i></th></tr>
<tr><th align='left' bgcolor='#e9b96e' colspan='5'>Call Stack</th></tr>
<tr><th align='center' bgcolor='#eeeeec'>#</th><th align='left' bgcolor='#eeeeec'>Time</th><th align='left' bgcolor='#eeeeec'>Memory</th><th align='left' bgcolor='#eeeeec'>Function</th><th align='left' bgcolor='#eeeeec'>Location</th></tr>
<tr><td bgcolor='#eeeeec' align='center'>1</td><td bgcolor='#eeeeec' align='center'>0.6349</td><td bgcolor='#eeeeec' align='right'>16449832</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Core\ErrorHandler->handleFatalError(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>0</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>2</td><td bgcolor='#eeeeec' align='center'>0.6363</td><td bgcolor='#eeeeec' align='right'>16455104</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Core\ErrorHandler->handleApiFatalError(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>50</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>3</td><td bgcolor='#eeeeec' align='center'>0.6364</td><td bgcolor='#eeeeec' align='right'>16455104</td><td bgcolor='#eeeeec'>Crowdin\App\Src\Core\ErrorHandler->showApiError(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>68</td></tr>
<tr><td bgcolor='#eeeeec' align='center'>4</td><td bgcolor='#eeeeec' align='center'>0.6365</td><td bgcolor='#eeeeec' align='right'>16456080</td><td bgcolor='#eeeeec'><a href='http://www.php.net/function.header' target='_new'>header</a>
(  )</td><td title='/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php' bgcolor='#eeeeec'>.../ErrorHandler.php<b>:</b>484</td></tr>
<tr><th align='left' colspan='5' bgcolor='#e9b96e'>Variables in local scope (#3)</th></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$code&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:484:</small><small>int</small> <font color='#4e9a06'>0</font>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$json_output&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:484:</small>
<b>array</b> <i>(size=2)</i>
  'success' <font color='#888a85'>=&gt;</font> <small>boolean</small> <font color='#75507b'>false</font>
  'error' <font color='#888a85'>=&gt;</font> 
    <b>array</b> <i>(size=2)</i>
      'code' <font color='#888a85'>=&gt;</font> <small>int</small> <font color='#4e9a06'>0</font>
      'message' <font color='#888a85'>=&gt;</font> <small>string</small> <font color='#cc0000'>'Unknown internal error'</font> <i>(length=22)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$message&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:484:</small><small>string</small> <font color='#cc0000'>'Unknown internal error'</font> <i>(length=22)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$output&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:484:</small><small>string</small> <font color='#cc0000'>'{&#10;    &quot;success&quot;: false,&#10;    &quot;error&quot;: {&#10;        &quot;code&quot;: 0,&#10;        &quot;message&quot;: &quot;Unknown internal error&quot;&#10;    }&#10;}&#10;'</font> <i>(length=110)</i>
</pre></td></tr>
<tr><td colspan='2' align='right' bgcolor='#eeeeec' valign='top'><pre>$xmlOutput&nbsp;=</pre></td><td colspan='3' bgcolor='#eeeeec'><pre class='xdebug-var-dump' dir='ltr'>
<small>/home/crowdin/valeriy/crowdin-backend/src/Core/ErrorHandler.php:484:</small><font color='#3465a4'>*uninitialized*</font>
</pre></td></tr>
</table></font>
{
    "success": false,
    "error": {
        "code": 0,
        "message": "Unknown internal error"
    }
}
