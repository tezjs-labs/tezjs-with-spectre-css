<script >
export default {
  layoutName:'default',
};
</script>
<template>
<div class="p-centered col-4 col-md-12 mt-2 col-lg-6 section-padding">
    <div class="empty s-rounded">
        <div class="empty-icon">
            <i class="icon icon-people icon-4x"></i>
        </div>
        <form class="form-horizontal">
            <div class="form-group text-left">
                <div class="col-2 col-sm-12 mr-2">
                    <label class="form-label">Name:</label>
                </div>
                <div class="col-9 col-sm-12 mb-2">
                    <input type="text" class="form-input"  placeholder="Name" />
                </div>
                <div class="col-2 col-sm-12 mr-2">
                    <label class="form-label ">Email:</label>
                </div>
                <div class="col-9 col-sm-12">
                    <input type="email" class="form-input" placeholder="Email" />
                </div>    
            </div>
            <div class="form-group text-left">
                <div class="col-2 col-sm-12 mr-2">
                    <label class="form-label">Gender:</label>
                </div>
                <div class="col-9 col-sm-12">
                    <label class="form-radio">
                        <input type="radio" name="gender" checked>
                        <i class="form-icon "></i> Male
                    </label>
                    <label class="form-radio">
                        <input type="radio" name="gender">
                        <i class="form-icon"></i> Female
                    </label>
                </div> 
            </div>
            <div class="form-group text-left">
                <div class="col-2 col-sm-12 mr-2">
                    <label class="form-label">Phone:</label>
                </div>
                <div class="col-9 col-sm-12 mb-2">
                    <input type="text" class="form-input"  placeholder="Phone Number" />
                </div>
            </div>
            <div class="form-group text-left">
                <div class="col-2 col-sm-12 mr-2">
                    <label class="form-label">BirthDate:</label>
                </div>
                <div class="col-9 col-sm-12 mb-2">
                    <input type="date" class="form-input"/>
                </div>
            </div>
            <div class="form-group text-left">
                <div class="col-2 col-sm-12 mr-2">
                    <label class="form-label">Address:</label>
                </div>
                <div class="col-9 col-sm-12 mb-2">
                    <textarea class="form-input" placeholder="Enter Your Address" rows="3"></textarea>
                </div>
            </div>
            <div class="form-group">
                    <label class="form-checkbox">
                        <input type="checkbox">
                        <i class="form-icon"></i> I accept the terms and conditions
                    </label>
            </div>
            <div class="empty-action">
                <button class="btn btn-primary btn-lg">Submit</button>
            </div>
        </form>
    </div>
</div>

 
</template>


