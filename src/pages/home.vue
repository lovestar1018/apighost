<template>
  <div class="content-wrapper">

    <div class="alert-wrapper">


      <div class="flash-container flash-container-page">
      </div>


    </div>
    <div class="container-fluid container-limited ">
      <div class="content" id="content-body">
        <div class="blank-state blank-state-welcome">
          <h2 class="blank-state-welcome-title">
            Welcome to GitLab
          </h2>
          <p class="blank-state-text">
            Code, test, and deploy together
          </p>
        </div>
        <div class="blank-state">
          <div class="blank-state-icon">
            <svg width="50" height="50" viewBox="0 0 16 16">
              <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                <g id="Group" fill="#303030">
                  <path d="M15.6667,10.0105 L10.3337,10.0105 C10.1497,10.0105 9.9997,10.1775 9.9997,10.3845 L9.9997,15.6145 C9.9997,15.8215 10.1497,15.9885 10.3337,15.9885 L15.6667,15.9885 C15.8507,15.9885 15.9997,15.8215 15.9997,15.6145 L15.9997,10.3845 C15.9997,10.1775 15.8507,10.0105 15.6667,10.0105 L15.6667,10.0105 L15.6667,10.0105 Z M11.9997,14.0105 L13.9997,14.0105 L13.9997,12.0105 L11.9997,12.0105 L11.9997,14.0105 L11.9997,14.0105 Z" id="Fill-11"></path>
                  <path d="M5.6667,10.0105 L0.3337,10.0105 C0.1497,10.0105 -0.0003,10.1775 -0.0003,10.3845 L-0.0003,15.6145 C-0.0003,15.8215 0.1497,15.9885 0.3337,15.9885 L5.6667,15.9885 C5.8507,15.9885 5.9997,15.8215 5.9997,15.6145 L5.9997,10.3845 C5.9997,10.1775 5.8507,10.0105 5.6667,10.0105 L5.6667,10.0105 L5.6667,10.0105 Z M1.9997,14.0105 L3.9997,14.0105 L3.9997,12.0105 L1.9997,12.0105 L1.9997,14.0105 L1.9997,14.0105 Z" id="Fill-8"></path>
                  <polygon id="Stroke-1" points="12.5 7.5834 3.5 7.5834 3.5 9.5834 12.5 9.5834"></polygon>
                  <polygon id="Stroke-3" points="9 9.0834 9 5.0834 7 5.0834 7 9.0834"></polygon>
                  <polygon id="Stroke-4" points="4 11.0834 4 7.5834 2 7.5834 2 11.0834"></polygon>
                  <polygon id="Stroke-6" points="14 11.0834 14 7.5834 12 7.5834 12 11.0834"></polygon>
                  <path d="M11.6667,6.21724894e-15 L4.3337,6.21724894e-15 C4.1497,6.21724894e-15 3.9997,0.167 3.9997,0.374 L3.9997,6.604 C3.9997,6.811 4.1497,6.978 4.3337,6.978 L11.6667,6.978 C11.8507,6.978 11.9997,6.811 11.9997,6.604 L11.9997,0.374 C11.9997,0.167 11.8507,6.21724894e-15 11.6667,6.21724894e-15 L11.6667,6.21724894e-15 L11.6667,6.21724894e-15 Z M5.9997,5 L9.9997,5 L9.9997,2 L5.9997,2 L5.9997,5 L5.9997,5 Z" id="Fill-14"></path>
                </g>
              </g>
            </svg>

          </div>
          <h3 class="blank-state-title">
            You can create a group for several dependent projects.
          </h3>
          <p class="blank-state-text">
            Groups are the best way to manage projects and members.
          </p>
          <a class="btn btn-new" href="/groups_new">New group
          </a></div>
        <div class="blank-state">
          <div class="blank-state-icon">
            <svg width="50" height="50" viewBox="0 0 16 16">
              <path d="M6,6 L12,6 L12,5 L6,5 L6,6 Z M6,8 L12,8 L12,7 L6,7 L6,8 Z M6,10 L12,10 L12,9 L6,9 L6,10 Z M6,12 L12,12 L12,11 L6,11 L6,12 Z M4,6 L5,6 L5,5 L4,5 L4,6 Z M4,8 L5,8 L5,7 L4,7 L4,8 Z M4,10 L5,10 L5,9 L4,9 L4,10 Z M4,12 L5,12 L5,11 L4,11 L4,12 Z M13,3 L10,3 L10,4 L6,4 L6,3 L3,3 L3,13 L13,13 L13,3 Z M2,14 L14,14 L14,2 L2,2 L2,14 Z M1,0 C0.448,0 0,0.448 0,1 L0,15 C0,15.552 0.448,16 1,16 L15,16 C15.552,16 16,15.552 16,15 L16,1 C16,0.448 15.552,0 15,0 L1,0 Z" fill="#7F7E7E" fill-rule="evenodd"></path>
            </svg>

          </div>
          <h3 class="blank-state-title">
            You don't have access to any projects right now
          </h3>
          <p class="blank-state-text">
            You can create up to
            <strong>100,000</strong>
            projects.
          </p>
          <a class="btn btn-new" href="/projects_new">New project
          </a></div>

      </div>
    </div>
  </div>
</template>

<style lang="styl" rel="stylesheet/stylus" scoped type="text/css">

</style>

<script type="text/ecmascript-6">
  import BasePage from 'src/extend/BasePage'
  export default{
    mixins: [ BasePage ],
    components: {},
    name: 'home',
    mounted: function () {

    }
  }
</script>
