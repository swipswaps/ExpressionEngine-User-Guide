<!--
    This source file is part of the open source project
    ExpressionEngine User Guide (https://github.com/ExpressionEngine/ExpressionEngine-User-Guide)

    @link      https://expressionengine.com/
    @copyright Copyright (c) 2003-2020, Packet Tide, LLC (https://www.packettide.com)
    @license   https://expressionengine.com/license Licensed under Apache License, Version 2.0
-->

# Status Menu

Allows the entry's status to be set:

    {status_menu}
      <p>Status<br>
        <select name="status">
          {select_options}
        </select>
      </p>
    {/status_menu}

Or use the alternative syntax:

    <label for="status">Status</label>
    <select name="status" id="status">
      {statuses}
        <option value="{status}"{selected}>{status}</option>
      {/statuses}
    </select>
