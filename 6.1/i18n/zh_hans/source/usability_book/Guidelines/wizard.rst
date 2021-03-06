.. i18n: =====================
.. i18n: Configuration wizards
.. i18n: =====================
..

=====================
配置向导
=====================

.. i18n: A common layout for all wizards
.. i18n: -------------------------------
..

向导的通用布局
-------------------------------

.. i18n: * Adapted title to each application : as introduced, chosen application leads to one configuration wizard. The configuration wizard must have a title related to the application. 
.. i18n: * Picture and information on the left : all wizards must have one business picture and an explanation text regarding the business application to configure.  
.. i18n: * Objects (Documents) to configure on the right : all objects related to the application must be chosen with selection box. Must be placed on the right.
.. i18n: * Allow user to Skip or Configure : Each wizard must have 2 buttons, one to Skip and one to configure. These buttons must be placed on the bottom right. 
.. i18n: * Progress bar : to allow user see where he is in configuration, all wizards have to have a progress bar with the percentage of completion of database.
.. i18n: * Separators : Each part of the wizard must be separated by a separator bar 
..

* 标题要符合应用套件内容：正如之前介绍，选择安装应用之后就会有一个配置向导。该配置向导的标题必须与应用套件相关。
* 图片和说明性信息放在左边：所有向导都需要相关的图片和说明性的文字，告诉用户如何配置。
* 可配置对象（文件）放在右边：所有可配置对象应该可以选择和配置，放在配置向导的右边。
* 允许用户跳过配置：所有配置向导都必须有2个按钮，“跳过” 和 “配置”，放在配置向导右下角。
* 进度条：允许用户看到进行到哪一步了，所有应用都应该有一个百分比的进度条来显示完成进度。
* 分隔符：每个配置部分都应该用分割栏分开布局。

.. i18n: Configuration wizards are optional
.. i18n: -----------------------------------
..

配置向导应该是可选的
-----------------------------------

.. i18n: Configuration wizards are optional. The system must be usable and configured by default even if the administrator skips all steps during the configuration process. Configuration wizards are available only to:
..

配置向导是可选的。系统应该可以使用默认配置，即使管理员在配置过程中跳过所有步骤。配置向导仅适用于：

.. i18n: 1. Propose new features to install (a set of modules)
.. i18n: 2. Change the default configuration of the system (and not configure the system !)
..

1. 提供新功能安装（一系列模块）
2. 更改系统的默认配置（而不是配置系统！）

.. i18n: Configuration wizards are part of the applications
.. i18n: --------------------------------------------------
..

配置向导为应用的一部分
--------------------------------------------------

.. i18n: Most of the application wizards must be part of one application. Be sure that:
..

大多数的应用向导必须是应用套件的一部分。请务必做到：

.. i18n: * The application this configuration wizard belongs to is explicit
.. i18n: * Terminology are dedicated to the application context. As an example, in a project management application, don't talk about analytic account or entries but talk about projects and timesheets. Avoid configuration wizards that are related to several applications.
..

* 明确配置向导向导属于某个应用套件
* 术语独立于应用套件的上下文。例如，在项目管理应用中，不要讨论辅助核算或凭证，要讨论项目或时间表。避免涉及到多个应用套件的配置向导。

.. i18n: Configuration wizards and extended/simplified views
.. i18n: ---------------------------------------------------
..

配置向导与扩展/简单试图
---------------------------------------------------

.. i18n: Be sure you use extended/simplified views features also in configuration wizards. In order to simplify the configuration process, some options or wizards must be available in extended views only.
..

扩展/简单试图也同样适用于配置向导。为简化配置过程，有些配置选项仅在扩展试图中显示。
