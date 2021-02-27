<template>
  <header id="sc-header">
	<nav class="uk-navbar uk-navbar-container" data-uk-navbar="mode: click; duration: 360">
		<div class="uk-navbar-left nav-overlay-small uk-margin-right uk-navbar-aside">
            			<a href="#" id="sc-sidebar-main-toggle"><i class="mdi mdi-backburger sc-menu-close"></i><i class="mdi mdi-menu sc-menu-open"></i></a>
            			<div class="sc-brand uk-visible@s">
				<a href="dashboard-v1.html"><img src="assets/img/logo.png" alt=""></a>
			</div>
		</div>
    		<div class="uk-navbar-left nav-overlay uk-margin-right uk-visible@m">
			<ul class="uk-navbar-nav">
				<li>
					<a href="javascript:void(0)" class="md-color-white sc-padding-remove-left"><i class="mdi mdi-view-grid"></i></a>
					<div class="uk-navbar-dropdown sc-padding-medium">
						<div class="uk-child-width-1-2 uk-child-width-1-3@s uk-grid uk-grid-small" data-uk-grid>
							<div>
								<a href="pages-mailbox.html" class="uk-flex uk-flex-column uk-flex-middle uk-box-shadow-hover-small sc-round sc-padding-small">
									<i class="mdi mdi-email-outline sc-icon-32 sc-text-lh-1 md-color-green-700"></i>
									<span class="uk-text-medium sc-color-primary">Mailbox</span>
								</a>
							</div>
							<div>
								<a href="pages-poi_listing.html" class="uk-flex uk-flex-column uk-flex-middle uk-box-shadow-hover-small sc-round sc-padding-small">
									<i class="mdi mdi-map-marker sc-icon-32 sc-text-lh-1 md-color-red-700"></i>
									<span class="uk-text-medium sc-color-primary">POI</span>
								</a>
							</div>
							<div>
								<a href="pages-chat.html" class="uk-flex uk-flex-column uk-flex-middle uk-box-shadow-hover-small sc-round sc-padding-small">
									<i class="mdi mdi-message-outline sc-icon-32 sc-text-lh-1 md-color-purple-700"></i>
									<span class="uk-text-medium sc-color-primary">Chat</span>
								</a>
							</div>
							<div>
								<a href="plugins-calendar.html" class="uk-flex uk-flex-column uk-flex-middle uk-box-shadow-hover-small sc-round sc-padding-small">
									<i class="mdi mdi-calendar sc-icon-32 sc-text-lh-1 md-color-light-blue-700"></i>
									<span class="uk-text-medium sc-color-primary">Calendar</span>
								</a>
							</div>
							<div>
								<a href="pages-user_profile.html" class="uk-flex uk-flex-column uk-flex-middle uk-box-shadow-hover-small sc-round sc-padding-small">
									<i class="mdi mdi-account sc-icon-32 sc-text-lh-1 md-color-blue-grey-700"></i>
									<span class="uk-text-medium sc-color-primary">Profile</span>
								</a>
							</div>
							<div>
								<a href="plugins-charts.html" class="uk-flex uk-flex-column uk-flex-middle uk-box-shadow-hover-small sc-round sc-padding-small">
									<i class="mdi mdi-chart-multiline sc-icon-32 sc-text-lh-1 md-color-amber-700"></i>
									<span class="uk-text-medium sc-color-primary">Charts</span>
								</a>
							</div>
						</div>
					</div>
				</li>
			</ul>
		</div>
    		<div class="nav-overlay nav-overlay-small uk-navbar-right uk-flex-1" hidden>
			<a class="uk-navbar-toggle uk-visible@m" data-uk-toggle="target: .nav-overlay; animation: uk-animation-slide-top" href="#">
				<i class="mdi mdi-close sc-icon-24"></i>
			</a>
			<a class="uk-navbar-toggle uk-hidden@m uk-padding-remove-left" data-uk-toggle="target: .nav-overlay-small; animation: uk-animation-slide-top" href="#">
				<i class="mdi mdi-close sc-icon-24"></i>
			</a>
			<div class="uk-navbar-item uk-width-expand uk-padding-remove-right">
				<form class="uk-search uk-search-navbar uk-width-1-1 uk-flex">
					<input class="uk-search-input" type="search" placeholder="Search..." autofocus>
					<button class="sc-button sc-button-small sc-button-icon sc-button-flat uk-margin-small-left" type="button"><i class="mdi mdi-magnify sc-icon-24 md-color-white"></i></button>
				</form>
			</div>
		</div>
		<div class="nav-overlay nav-overlay-small uk-navbar-right">
			<ul class="uk-navbar-nav">
				<li>
					<a class="uk-navbar-toggle uk-visible@m" href="#" data-uk-toggle="target: .nav-overlay; animation: uk-animation-slide-top"><i class="mdi mdi-magnify"></i></a>
                    <a class="uk-navbar-toggle uk-hidden@m" href="#" id="sc-search-main-toggle-mobile" data-uk-toggle="target: .nav-overlay-small; animation: uk-animation-slide-top"><i class="mdi mdi-magnify"></i></a>
				</li>
				<li class="uk-visible@l">
					<a href="#" id="sc-js-fullscreen-toggle"><i class="mdi mdi-fullscreen sc-js-el-hide"></i><i class="mdi mdi-fullscreen-exit sc-js-el-show"></i></a>
				</li>
				<li class="uk-visible@s">
					<a href="#" class="sc-text-semibold">
						EN
					</a>
					<div class="uk-navbar-dropdown uk-dropdown-small">
						<ul class="uk-nav uk-navbar-dropdown-nav">
							<li><a href="#">Deutsch</a></li>
							<li><a href="#">Español</a></li>
							<li><a href="#">Français</a></li>
						</ul>
					</div>
				</li>
				<li>
					<a href="#">
						<span class="mdi mdi-email"></span>
					</a>
					<div class="uk-navbar-dropdown sc-padding-remove">
						<div class="uk-panel uk-panel-scrollable uk-height-medium">
							<ul class="uk-list uk-list-divider sc-js-edge-fix">
								<li class="sc-list-group">
									<div class="sc-list-addon">
										<span class="sc-avatar-initials md-color-white md-bg-red-500" title="maxime95">MO</span>
									</div>
									<a href="#" class="sc-list-body uk-display-block">
										<span class="uk-text-small uk-text-muted uk-width-expand">03:16 PM</span>
										<span class="uk-display-block uk-text-truncate">Explicabo mollitia rerum veritatis quam et ratione.</span>
									</a>
								</li>
								<li class="sc-list-group">
									<div class="sc-list-addon">
										<img src="assets/img/avatars/avatar_05_sm.png" class="sc-avatar " alt="jennings54"/>
									</div>
									<a href="#" class="sc-list-body uk-display-block">
										<div class="uk-text-small uk-text-muted uk-width-expand">Jan 19, 2020</div>
										<span class="uk-display-block uk-text-truncate">Facilis debitis nisi debitis aut voluptatem a voluptas ipsa qui vitae.</span>
									</a>
								</li>
								<li class="sc-list-group">
									<div class="sc-list-addon">
										<span class="sc-avatar-initials md-color-white md-bg-light-green-500" title="nick32">KS</span>
									</div>
									<a href="#" class="sc-list-body uk-display-block">
										<span class="uk-text-small uk-text-muted uk-width-expand">01:16 PM</span>
										<span class="uk-display-block uk-text-truncate">Tenetur veritatis quo eos aut quis dolor cum debitis placeat.</span>
									</a>
								</li>
								<li class="sc-list-group">
									<div class="sc-list-addon">
										<img src="assets/img/avatars/avatar_06_sm.png" class="sc-avatar " alt="wprice"/>
									</div>
									<a href="#" class="sc-list-body uk-display-block">
										<span class="uk-text-small uk-text-muted uk-width-expand">Jan 18, 2020</span>
										<span class="uk-display-block uk-text-truncate">Esse ipsum impedit quam adipisci tempora vel ullam magni harum sunt.</span>
									</a>
								</li>
								<li class="sc-list-group">
									<div class="sc-list-addon">
										<img src="assets/img/avatars/avatar_02_sm.png" class="sc-avatar " alt="ytremblay"/>
									</div>
									<a href="#" class="sc-list-body uk-display-block">
										<span class="uk-text-small uk-text-muted uk-width-expand">Jan 16, 2020</span>
										<span class="uk-display-block uk-text-truncate">Molestiae consectetur quos excepturi error nemo accusantium tenetur.</span>
									</a>
								</li>
								<li class="sc-list-group">
									<div class="sc-list-addon">
										<span class="sc-avatar-initials md-color-white md-bg-purple-500" title="cummerata.mable">FA</span>
									</div>
									<a href="#" class="sc-list-body uk-display-block">
										<span class="uk-text-small uk-text-muted uk-width-expand">Jan 14, 2020</span>
										<span class="uk-display-block uk-text-truncate">Aut totam tenetur autem ut qui facere vel.</span>
									</a>
								</li>
							</ul>
						</div>
						<a href="pages-mailbox.html" class="uk-flex uk-text-small sc-padding-small-ends sc-padding-medium">Show all in mailbox</a>
					</div>
				</li>
				<li class="uk-visible@s">
					<a href="#">
						<span class="mdi mdi-bell uk-display-inline-block">
							<span class="sc-indicator md-bg-color-red-600"></span>
						</span>
					</a>
					<div class="uk-navbar-dropdown md-bg-grey-100">
                        <div class="sc-padding-medium sc-padding-small-ends">
                            <div class="uk-text-right uk-margin-medium-bottom">
                                <button class="sc-button sc-button-outline sc-button-mini sc-js-clear-alerts">Clear all</button>
                            </div>
                            <ul class="uk-list uk-margin-remove" id="sc-header-alerts">
                                <li class="sc-border sc-round md-bg-white">
                                    <div class="uk-margin-right uk-margin-small-left"><i class="mdi mdi-alert-outline md-color-red-600"></i></div>
                                    <div class="uk-flex-1 uk-text-small">
                                        Information Page Not Found!
                                    </div>
                                </li>
                                <li class="uk-margin-small-top sc-border sc-round md-bg-white">
                                    <div class="uk-margin-right uk-margin-small-left"><i class="mdi mdi-email-check-outline md-color-blue-600"></i></div>
                                    <div class="uk-flex-1 uk-text-small">
                                        A new password has been sent to your e-mail address.
                                    </div>
                                </li>
                                <li class="uk-margin-small-top sc-border sc-round md-bg-white">
                                    <div class="uk-margin-right uk-margin-small-left"><i class="mdi mdi-alert-outline md-color-red-600"></i></div>
                                    <div class="uk-flex-1 uk-text-small">
                                        You do not have permission to access the API!
                                    </div>
                                </li>
                                <li class="uk-margin-small-top sc-border sc-round md-bg-white">
                                    <div class="uk-margin-right uk-margin-small-left"><i class="mdi mdi-check-all md-color-light-green-600"></i></div>
                                    <div class="uk-flex-1 uk-text-small">
                                        Your enquiry has been successfully sent.
                                    </div>
                                </li>
                            </ul>
                            <div class="uk-text-medium uk-text-center sc-js-empty-message sc-text-semibold sc-padding-ends" style="display: none">No alerts!</div>
                        </div>
					</div>
				</li>
				<li>
					<a href="#"><img src="assets/img/avatars/avatar_default_sm.png" alt=""></a>
					<div class="uk-navbar-dropdown uk-dropdown-small">
						<ul class="uk-nav uk-nav-navbar">
							<li><a href="pages-user_profile.html">Profile</a></li>
							<li><a href="pages-settings.html">Settings</a></li>
							<li><a href="login_page.html">Log Out</a></li>
						</ul>
					</div>
				</li>
			</ul>
            <a href="#" class="sc-js-offcanvas-toggle md-color-white uk-margin-left uk-hidden@l">
	            <i class="mdi mdi-menu sc-offcanvas-open"></i>
	            <i class="mdi mdi-arrow-right sc-offcanvas-close"></i>
            </a>
		</div>
	</nav>
</header>

<aside id="sc-sidebar-main" class="sc-sidebar-info-fixed">
    <div class="uk-offcanvas-bar">
	    <div class="sc-sidebar-main-scrollable" data-sc-scrollbar="visible-y">
	        <ul class="sc-sidebar-menu uk-nav">
	        
	            
	                <li class="sc-sidebar-menu-heading"><span>Applications</span></li>
	                
	            	        
	            	            <li title="Chat">
	                <a href="pages-chat.html">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-message-outline"></i>
	                    
	                    </span><span class="uk-nav-title">Chat</span>
	                </a>
	                	            </li>
	            	        
	            	            <li title="Invoices">
	                <a href="pages-invoices.html">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-receipt"></i>
	                    
	                    </span><span class="uk-nav-title">Invoices</span>
	                </a>
	                	            </li>
	            	        
	            	            <li title="Mailbox">
	                <a href="pages-mailbox.html">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-email-outline"></i>
	                    
	                    </span><span class="uk-nav-title">Mailbox</span>
	                </a>
	                	            </li>
	            	        
	            	            <li title="Task Board">
	                <a href="pages-task_board.html">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-calendar-text"></i>
	                    
	                    </span><span class="uk-nav-title">Task Board</span>
	                </a>
	                	            </li>
	            	        
	            	            <li title="Notes">
	                <a href="pages-notes.html">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-note-outline"></i>
	                    
	                    </span><span class="uk-nav-title">Notes</span>
	                </a>
	                	            </li>
	            	        
	            
	                <li class="sc-sidebar-menu-heading"><span>Menu</span></li>
	                
	            	        
	            	            <li title="Dashboards">
	                <a href="#">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-view-dashboard-variant"></i>
	                    
	                    </span><span class="uk-nav-title">Dashboards</span>
	                </a>
	                
	                    <ul class="sc-sidebar-menu-sub">
	                    	                        
	                        <li>
	                            
	                                <a href="dashboard-v1.html">		                                		                                Dashboard 1	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="dashboard-v2.html">		                                		                                Dashboard 2	                                </a>
	                            
	                        </li>
	                        
	                        
	                    
	                    </ul>
	                	            </li>
	            	        
	            	            <li title="Forms">
	                <a href="#">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-format-line-style"></i>
	                    
	                    </span><span class="uk-nav-title">Forms</span>
	                </a>
	                
	                    <ul class="sc-sidebar-menu-sub">
	                    	                        
	                        <li>
	                            
	                                <a href="forms-regular_elements.html">		                                		                                Regular Elements	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="forms-advanced_elements.html">		                                		                                Advanced Elements	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="forms-dynamic_fields.html">		                                		                                Dynamic Fields	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="forms-validation.html">		                                		                                Validation	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        	                            	                                <li>
	                                    <a href="#">Form Examples</a>	                                    <ul>
	                                    	                                        <li>
	                                            <a href="forms_examples-advertising_evaluation_form.html">		                                            		                                            Advertising Evaluation Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-booking_form.html">		                                            		                                            Booking Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-car_rental_form.html">		                                            		                                            Car Rental Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-checkout_form.html">		                                            		                                            Checkout Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-contact_forms.html">		                                            		                                            Contact Forms	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-job_application_form.html">		                                            		                                            Job Application Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-medical_history_form.html">		                                            		                                            Medical History Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-registration_form.html">		                                            		                                            Registration Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-rental_application_form.html">		                                            		                                            Rental Application Form	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_examples-transaction_feedback_form.html">		                                            		                                            Transaction Feedback Form	                                            </a>
	                                        </li>
	                                    
	                                    </ul>
	                                </li>
	                            
	                        
	                        
	                    	                        	                            	                                <li>
	                                    <a href="#">Wizard</a>	                                    <ul>
	                                    	                                        <li>
	                                            <a href="forms_wizard-horizontal.html">		                                            		                                            Horizontal	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_wizard-horizontal_minimal.html">		                                            		                                            Horizontal Minimal	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_wizard-vertical.html">		                                            		                                            Vertical	                                            </a>
	                                        </li>
	                                    	                                        <li>
	                                            <a href="forms_wizard-vertical_minimal.html">		                                            		                                            Vertical Minimal	                                            </a>
	                                        </li>
	                                    
	                                    </ul>
	                                </li>
	                            
	                        
	                        
	                    	                        	                            	                                <li class="sc-sidebar-menu-heading"><span>WYSIWYG Editors</span></li>
	                                	                                    <li>
	                                    	                                        <a href="forms_wysiwyg-ckeditor.html">		                                        		                                        CKEditor	                                        </a>
	                                    	                                    </li>
	                                	                                    <li>
	                                    	                                        <a href="forms_wysiwyg-tinymce.html">		                                        		                                        TinyMCE	                                        </a>
	                                    	                                    </li>
	                                
	                            
	                        
	                        
	                    
	                    </ul>
	                	            </li>
	            	        
	            	            <li title="Components">
	                <a href="#">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-puzzle"></i>
	                    
	                    </span><span class="uk-nav-title">Components</span>
	                </a>
	                
	                    <ul class="sc-sidebar-menu-sub">
	                    	                        
	                        <li class="sc-page-active">
	                            
	                                <a href="components-accordion.html">		                                		                                Accordion	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-alert.html">		                                		                                Alert	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-animations.html">		                                		                                Animations	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-avatars.html">		                                		                                Avatars	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-badge_label.html">		                                		                                Badge, Label	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-base.html">		                                		                                Base	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-breadcrumb.html">		                                		                                Breadcrumb	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-buttons.html">		                                		                                Buttons	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-fab_buttons.html">		                                			                                <span class="uk-label">new</span>
		                                		                                FAB Buttons	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-cards.html">		                                		                                Cards	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-color_palette.html">		                                		                                Color Palette	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-drop_dropdowns.html">		                                			                                <span class="uk-label">new</span>
		                                		                                Drop/Dropdowns	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-filters.html">		                                		                                Filters	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-footer.html">		                                		                                Footer	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-grid.html">		                                		                                Grid	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-icons.html">		                                			                                <span class="uk-label">new</span>
		                                		                                Icons	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-lists.html">		                                		                                Lists	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-masonry.html">		                                		                                Masonry	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-modals_dialogs.html">		                                		                                Modals/Dialogs	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-notifications.html">		                                		                                Notifications	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-pagination.html">		                                		                                Pagination	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-progress_spinners.html">		                                		                                Progress/Spinners	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-scrollable.html">		                                		                                Scrollable	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-slider.html">		                                		                                Slider	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-sortable.html">		                                		                                Sortable	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-tables.html">		                                		                                Tables	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-tabs.html">		                                		                                Tabs	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-timeline.html">		                                		                                Timeline	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-toolbar.html">		                                		                                Toolbar	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="components-tooltips.html">		                                		                                Tooltips	                                </a>
	                            
	                        </li>
	                        
	                        
	                    
	                    </ul>
	                	            </li>
	            	        
	            	            <li title="Pages">
	                <a href="#">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-application"></i>
	                    
	                    </span><span class="uk-nav-title">Pages</span>
	                </a>
	                
	                    <ul class="sc-sidebar-menu-sub">
	                    	                        
	                        <li>
	                            
	                                <a href="pages-blank.html">		                                		                                Blank	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-blank_header_expanded.html">		                                		                                Blank (expanded header)	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-contact_list.html">		                                		                                Contact List	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-contact_list_single.html">		                                		                                Contact List (single)	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        	                            	                                <li class="sc-sidebar-menu-heading"><span>Error Pages</span></li>
	                                	                                    <li>
	                                    	                                        <a href="error_404.html">		                                        		                                        Error 404	                                        </a>
	                                    	                                    </li>
	                                	                                    <li>
	                                    	                                        <a href="error_500.html">		                                        		                                        Error 500	                                        </a>
	                                    	                                    </li>
	                                
	                            
	                        
	                        	                            <li class="sc-sidebar-menu-separator"></li>
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-gallery.html">		                                		                                Gallery	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-help_faq.html">		                                		                                Help/Faq	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        	                            	                                <li class="sc-sidebar-menu-heading"><span>Issue Tracker</span></li>
	                                	                                    <li>
	                                    	                                        <a href="pages-issues_list.html">		                                        		                                        List View	                                        </a>
	                                    	                                    </li>
	                                	                                    <li>
	                                    	                                        <a href="pages-issue_details.html">		                                        		                                        Issue Details	                                        </a>
	                                    	                                    </li>
	                                
	                            
	                        
	                        	                            <li class="sc-sidebar-menu-separator"></li>
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="login_page.html">		                                		                                Login Page	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-poi_listing.html">		                                		                                POI listing	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-pricing_tables.html">		                                		                                Pricing Tables	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-settings.html">		                                		                                Settings	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="pages-user_profile.html">		                                		                                User Profile	                                </a>
	                            
	                        </li>
	                        
	                        
	                    
	                    </ul>
	                	            </li>
	            	        
	            	            <li title="Plugins">
	                <a href="#">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-power-plug"></i>
	                    
	                    </span><span class="uk-nav-title">Plugins</span>
	                </a>
	                
	                    <ul class="sc-sidebar-menu-sub">
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-ajax.html">		                                		                                Ajax	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-calendar.html">		                                		                                Calendar	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-charts.html">		                                		                                Charts	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-code_editor.html">		                                		                                Code Editor	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-data_grid.html">		                                		                                Data Grid	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-datatables.html">		                                		                                Datatables	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-diff_tool.html">		                                		                                Diff Tool	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-gantt_chart.html">		                                		                                Gantt Chart	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-google_maps.html">		                                		                                Google Maps	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-idle_timeout.html">		                                		                                Idle Timeout	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-image_cropper.html">		                                		                                Image Cropper	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-push_notifications.html">		                                		                                Push Notifications	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-tour.html">		                                		                                Tour	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-tree.html">		                                		                                Tree	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="plugins-vector_maps.html">		                                		                                Vector Maps	                                </a>
	                            
	                        </li>
	                        
	                        
	                    
	                    </ul>
	                	            </li>
	            	        
	            	            <li title="Layout">
	                <a href="#">
	                    	                        <span class="uk-nav-icon"><i class="mdi mdi-view-compact-outline"></i>
	                    
	                    </span><span class="uk-nav-title">Layout</span>
	                </a>
	                
	                    <ul class="sc-sidebar-menu-sub">
	                    	                        
	                        <li>
	                            
	                                <a href="layout-top_menu.html">		                                			                                <span class="uk-label">new</span>
		                                		                                Top Menu	                                </a>
	                            
	                        </li>
	                        
	                        
	                    	                        
	                        <li>
	                            
	                                <a href="layout-mini_sidebar.html">		                                			                                <span class="uk-label">new</span>
		                                		                                Mini Sidebar	                                </a>
	                            
	                        </li>
	                        
	                        
	                    
	                    </ul>
	                	            </li>
	            	        	            <li title="Multi-level">
	                <a href="#">
	                    <span class="uk-nav-icon"><i class="mdi mdi-format-line-weight"></i></span><span class="uk-nav-title">Multi level</span>
	                </a>
	                <ul class="sc-sidebar-menu-sub">
	                    <li><a href="#">Submenu 1</a></li>
	                    <li class="sc-js-submenu-trigger sc-has-submenu">
	                        <a href="#">Submenu 2</a>
	                        <ul>
	                            <li><a href="#">Submenu 2.1</a></li>
	                            <li>
	                                <a href="#">Submenu 2.2</a>
	                                <ul>
	                                    <li><a href="#">Submenu 2.2.1</a></li>
	                                    <li><a href="#">Submenu 2.2.2</a></li>
	                                    <li><a href="#">Submenu 2.2.3</a></li>
	                                </ul>
	                            </li>
	                            <li><a href="#">Submenu 2.3</a></li>
	                            <li><a href="#">Submenu 2.4</a></li>
	                        </ul>
	                    </li>
	                    <li><a href="#">Submenu 3</a></li>
	                    <li>
	                        <a href="#">Submenu 4</a>
	                        <ul>
	                            <li>
	                                <a href="#">Submenu 4.1</a>
	                                <ul>
	                                    <li><a href="#">Submenu 4.1.1</a></li>
	                                    <li><a href="#">Submenu 4.1.2</a></li>
	                                    <li><a href="#">Submenu 4.1.3</a></li>
	                                </ul>
	                            </li>
	                            <li><a href="#">Submenu 4.2</a></li>
	                            <li><a href="#">Submenu 4.3</a></li>
	                        </ul>
	                    </li>
	                </ul>
	            </li>
	        </ul>

	    </div>
        <div class="sc-sidebar-info">
            version: 2.2.0
        </div>
    </div>
</aside>
<div id="sc-page-wrapper">
	<div id="sc-page-content">
		<div class="uk-child-width-1-2@l" data-uk-grid>
			<div>
				<div class="uk-card uk-card-body uk-margin-medium">
					<ul data-uk-accordion>
						<li class="uk-open">
							<h3 class="uk-accordion-title">Item 1</h3>
							<div class="uk-accordion-content">
								Natus excepturi esse eos placeat ut est atque nihil voluptas nesciunt qui qui quo qui nihil eum accusamus vel voluptas impedit magnam veritatis aut ullam ea.							</div>
						</li>
						<li>
							<h3 class="uk-accordion-title">Item 2</h3>
							<div class="uk-accordion-content">
								Consequatur ut dicta dolor quia ipsum porro sequi sint quia voluptatem aspernatur est est ducimus autem eos iure voluptate iusto cumque est qui maiores cumque aut optio provident cumque nihil optio debitis ipsam amet voluptatem ab.							</div>
						</li>
						<li>
							<h3 class="uk-accordion-title">Item 3</h3>
							<div class="uk-accordion-content">
								Minus nemo sed sint ullam et voluptas sit in quos autem harum animi sit adipisci magnam ab ut quos qui ipsa quia aperiam voluptas qui accusamus ab incidunt repellat quia ducimus error facere aperiam voluptatem eos molestiae eligendi sunt eligendi magnam rerum assumenda.							</div>
						</li>
					</ul>
				</div>
				<div class="uk-card uk-margin">
					<div class="uk-card-header">
						<h2 class="uk-card-title">Outline</h2>
					</div>
					<div class="uk-card-body">
						<ul class="uk-accordion-outline" data-uk-accordion>
							<li class="uk-open">
								<h3 class="uk-accordion-title">Item 1</h3>
								<div class="uk-accordion-content">
									<div data-uk-grid>
										<div class="uk-width-1-3@m"><img src="assets/img/photos/ciaran-o-brien-769402-unsplash.jpg" class="uk-border-rounded uk-box-shadow" alt="ciaran-o-brien-769402-unsplash"/></div>
										<div class="uk-width-expand@m">Ut necessitatibus saepe dolor nostrum id dolorum alias ut voluptatem delectus modi aut est laborum ab distinctio consequatur ipsam et recusandae quis commodi harum repellat doloremque ad eveniet exercitationem rerum et magni animi expedita aliquid numquam praesentium sed ut recusandae in aut omnis non unde quibusdam facere rerum nobis impedit eum error alias consequatur expedita ratione tempore et velit.</div>
									</div>
								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title md-bg-light-blue-50">Item 2</h3>
								<div class="uk-accordion-content">
									Quis velit id et labore praesentium enim omnis mollitia alias vel porro consequatur qui amet sapiente exercitationem esse laudantium temporibus voluptatem id blanditiis in nesciunt omnis neque iste praesentium perspiciatis quidem animi unde fuga fuga doloribus dolor et blanditiis nostrum qui repellendus at blanditiis dolores labore eum ipsum dolore autem ab ut eaque harum corporis accusantium voluptatum aliquam numquam sunt earum.								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 3</h3>
								<div class="uk-accordion-content">
									Voluptas molestiae accusantium quam velit consequatur enim dolores officia unde doloremque molestiae quasi recusandae repudiandae non animi modi quis et corrupti dolor totam quis temporibus repellat suscipit cupiditate ut mollitia molestiae similique fuga excepturi nulla occaecati recusandae at doloremque consequatur quis dolor ut quas doloremque dignissimos ducimus voluptatem ea iste autem ipsum veniam nostrum maxime quasi et totam autem quas voluptatibus temporibus quis non iusto tenetur non alias in officiis deserunt qui inventore minus delectus inventore aut ut nemo architecto delectus.								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 4</h3>
								<div class="uk-accordion-content">
									Unde tenetur aliquid porro consequuntur soluta cupiditate et accusamus dolores asperiores illum labore quo quisquam illum odit qui tenetur repellat est aut deleniti dolores sit tempore eos magni dolorem nihil enim ipsum provident magnam repellat delectus nostrum illum incidunt voluptatum similique illo molestiae.								</div>
							</li>
						</ul>
					</div>
				</div>
				<div class="uk-card uk-margin">
					<div class="uk-card-header">
						<h2 class="uk-card-title">Alternative</h2>
					</div>
					<div class="uk-card-body">
					<ul class="uk-accordion-alt" data-uk-accordion>
							<li class="uk-open">
								<h3 class="uk-accordion-title md-bg-light-green-600 md-color-white">Item 1</h3>
								<div class="uk-accordion-content">
									<div data-uk-grid>
										<div class="uk-width-1-3@m"><img src="assets/img/photos/ciaran-o-brien-769402-unsplash.jpg" class="uk-border-rounded uk-box-shadow" alt="ciaran-o-brien-769402-unsplash"/></div>
										<div class="uk-width-expand@m">Totam numquam doloribus at eius accusamus minima nulla officia quod quia quam numquam magnam minus deleniti nisi dolorem sint sint molestiae beatae quis provident expedita velit exercitationem vitae qui quibusdam consequatur optio porro dolores dignissimos cumque non aut corporis veniam illo et at est optio quia sed omnis mollitia expedita assumenda esse quia.</div>
									</div>
								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 2</h3>
								<div class="uk-accordion-content">
									Ut fugiat eos quasi officia natus consectetur soluta rerum ullam quasi voluptatum incidunt consectetur occaecati itaque excepturi voluptate quo tenetur officia voluptatem culpa eum non architecto corrupti molestiae possimus officiis repudiandae sunt velit atque est et esse quibusdam eos totam modi illo ut sint et doloribus est voluptate voluptatibus similique eveniet optio qui id necessitatibus laudantium et hic iste est reprehenderit nostrum minus est nobis perspiciatis quis architecto qui sed natus dolor odit officia rerum aliquam.								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 3</h3>
								<div class="uk-accordion-content">
									Voluptate quisquam soluta maxime eum consequatur molestiae illum animi autem magnam et laborum ducimus placeat enim dolore suscipit nihil quod et ea magni omnis facilis et laudantium fuga nulla fugit nam tempore consectetur ut non doloremque quis dolores esse dignissimos nostrum et quia et soluta ad ipsum aut ducimus ratione quasi voluptatem eveniet provident soluta et quam et dolor et delectus aut repellat ipsum voluptates est natus voluptatem quam voluptatem voluptatibus quia deserunt culpa sed iusto enim est officia et.								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 4</h3>
								<div class="uk-accordion-content">
									Possimus qui in sit quaerat nulla quae quisquam aperiam corrupti recusandae est ad ipsa cupiditate itaque molestiae voluptatem soluta aliquam libero itaque incidunt tempore laudantium sint iste itaque illum sunt vitae molestiae cum ex molestiae rerum eos numquam sit nostrum pariatur est minus vero.								</div>
							</li>
						</ul>
					</div>
				</div>
			</div>
			<div>
				<div class="uk-card uk-margin">
					<div class="uk-card-header">
						<h2 class="uk-card-title">Multiple Open Items</h2>
					</div>
					<div class="uk-card-body">
						<ul data-uk-accordion="multiple: true">
							<li class="uk-open">
								<h3 class="uk-accordion-title">Item 1</h3>
								<div class="uk-accordion-content">
									Voluptatem aut aut doloribus nostrum culpa ad voluptas nemo a eum sed sint autem fugiat commodi sit accusamus occaecati tempora quae illo magnam distinctio a adipisci molestiae ut non nemo rerum soluta facilis praesentium nemo accusamus illo architecto et asperiores consequuntur autem tempore quae esse in ea molestiae dolorem deserunt sit magnam tenetur culpa corrupti dolorem et quibusdam tenetur quae reprehenderit sunt enim velit a doloremque et ratione.								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 2</h3>
								<div class="uk-accordion-content">
									Esse quia eius eius quis enim tenetur adipisci voluptas cum amet praesentium commodi nisi sunt veritatis dolores quaerat eum nihil quia dolorum debitis delectus aut itaque nobis quod aliquid explicabo quibusdam corporis nostrum accusamus quae eius laboriosam porro esse provident officiis totam totam amet voluptate molestiae et sit impedit nobis praesentium sit consectetur et maxime.								</div>
							</li>
							<li>
								<h3 class="uk-accordion-title">Item 3</h3>
								<div class="uk-accordion-content">
									Sunt ut rem et molestias quod eos in assumenda cupiditate quod quidem voluptatem officia aperiam et ullam in debitis quia assumenda dolores incidunt amet blanditiis qui quia perferendis placeat earum enim laudantium fugiat quia porro explicabo quas a ipsum suscipit unde fugit non veniam nihil velit voluptatibus sed nulla et occaecati facere ab blanditiis quia voluptatem.								</div>
							</li>
						</ul>
					</div>
				</div>
				<div class="uk-card uk-margin">
					<div class="uk-card-header">
						<h2 class="uk-card-title">Form Fields</h2>
					</div>
					<div class="uk-card-body">
						<div class="uk-child-width-1-2@s" data-uk-grid>
							<div>
								<label for="form-f-name">First Name</label>
								<input class="uk-input" id="form-f-name" type="text" data-sc-input>
							</div>
							<div>
								<label for="form-l-name">Last Name</label>
								<input class="uk-input" id="form-l-name" type="text" data-sc-input>
							</div>
						</div>
						<ul class="uk-margin" data-uk-accordion>
							<li>
								<h4 class="uk-accordion-title md-color-light-blue-800 uk-text-medium">Optional details</h4>
								<div class="uk-accordion-content">
									<div class="uk-child-width-1-2@s" data-uk-grid>
										<div>
											<label class="uk-form-label" for="form-m-name">Middle Name</label>
											<input class="uk-input" id="form-m-name" type="text" data-sc-input>
										</div>
										<div>
											<label class="uk-form-label" for="form-md-name">Maiden Name</label>
											<input class="uk-input" id="form-md-name" type="text" data-sc-input>
										</div>
									</div>
								</div>
							</li>
						</ul>
						<button class="uk-margin sc-button">Submit</button>
					</div>
				</div>
				<h5 class="uk-margin uk-margin-small-bottom">Accordion Menu</h5>
				<div class="uk-width-1-2@s uk-width-1-3@l">
					<div class="uk-card uk-card-body">
						<form>
							<ul data-uk-accordion>
								<li class="uk-open">
									<h3 class="uk-accordion-title"><i class="mdi mdi-ruler"></i>Size</h3>
									<div class="uk-accordion-content sc-padding-medium md-bg-grey-100 sc-round">
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-radio" type="radio" name="ac-size" id="ac-size-sm" data-sc-icheck><label for="ac-size-sm">Small</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-radio" type="radio" name="ac-size" id="ac-size-md" data-sc-icheck><label for="ac-size-md">Medium</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-radio" type="radio" name="ac-size" id="ac-size-lg" data-sc-icheck><label for="ac-size-lg">Large</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-radio" type="radio" name="ac-size" id="ac-size-xl" data-sc-icheck><label for="ac-size-xl">X-Large</label>
										</div>
									</div>
								</li>
								<li>
									<h3 class="uk-accordion-title"><i class="mdi mdi-palette"></i>Colors</h3>
									<div class="uk-accordion-content sc-padding-medium md-bg-grey-100 sc-round">
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-red" id="ac-red" data-sc-icheck><label for="ac-red" class="md-color-red-600">Red</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-blue" id="ac-blue" data-sc-icheck><label for="ac-blue" class="md-color-blue-600">Blue</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-green" id="ac-green" data-sc-icheck><label for="ac-green" class="md-color-green-600">Green</label>
										</div>
									</div>
								</li>
								<li>
									<h3 class="uk-accordion-title"><i class="mdi mdi-cash-usd"></i>Price</h3>
									<div class="uk-accordion-content sc-padding-medium md-bg-grey-100 sc-round">
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-price" id="ac-price-100" data-sc-icheck><label for="ac-price-100">$100.00</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-price" id="ac-price-500" data-sc-icheck><label for="ac-price-500">$500.00</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-price" id="ac-price-1000" data-sc-icheck><label for="ac-price-1000">$1000.00</label>
										</div>
										<div class="uk-margin-small uk-flex uk-flex-middle">
											<input class="uk-checkbox" type="checkbox" name="ac-price" id="ac-price-5000" data-sc-icheck><label for="ac-price-5000">$5000.00</label>
										</div>
									</div>
								</li>
							</ul>
						</form>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
</template>

<script>
export default {

}
</script>

<style>

</style>