<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Submission</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>
<body>
    <div class="container mt-5">
        <center>
            <table style="width:90%" border="1">
                <tr>
                    <td>
                        <form class="row g-3 needs-validation" novalidate id="myForm">
                            <h4>ข้อมูลผู้ส่ง</h4>
                            <div class="col-md-4">
                                <label for="senderName" class="form-label">ชื่อผู้ส่ง</label>
                                <input type="text" class="form-control" id="senderName" required>
                                <div class="valid-feedback">Looks good!</div>
                            </div>

                            <div class="col-md-4">
                                <label for="senderProvince" class="form-label">จังหวัด</label>
                                <select class="form-select" id="senderProvince" required>
                        
                                    <option selected disabled>เลือกจังหวัด</option>
                                    <option value="1">กรุงเทพมหานคร</option>
                                    <option value="2">กระบี่</option>
                                    <option value="3">กาญจนบุรี</option>
                                    <option value="4">กาฬสินธุ์</option>
                                    <option value="5">กำแพงเพชร</option>
                                    <option value="6">ขอนแก่น</option>
                                    <option value="7">จันทบุรี</option>
                                    <option value="8">ฉะเชิงเทรา</option>
                                    <option value="9">ชลบุรี</option>
                                    <option value="10">ชัยนาท</option>
                                    <option value="11">ชัยภูมิ</option>
                                    <option value="12">ชุมพร</option>
                                    <option value="13">ตรัง</option>
                                    <option value="14">ตราด</option>
                                    <option value="15">ตาก</option>
                                    <option value="16">นครนายก</option>
                                    <option value="17">นครปฐม</option>
                                    <option value="18">นครราชสีมา</option>
                                    <option value="19">นครศรีธรรมราช</option>
                                    <option value="20">นนทบุรี</option>
                                    <option value="21">นราธิวาส</option>
                                    <option value="22">น่าน</option>
                                    <option value="23">บุรีรัมย์</option>
                                    <option value="24">ปทุมธานี</option>
                                    <option value="25">ประจวบคีรีขันธ์</option>
                                    <option value="26">ปราจีนบุรี</option>
                                    <option value="27">ปัตตานี</option>
                                    <option value="28">พะเยา</option>
                                    <option value="29">เพชรบุรี</option>
                                    <option value="30">เพชรบูรณ์</option>
                                    <option value="31">แพร่</option>
                                    <option value="32">พังงา</option>
                                    <option value="33">ระนอง</option>
                                    <option value="34">ระยอง</option>
                                    <option value="35">ร้อยเอ็ด</option>
                                    <option value="36">ลพบุรี</option>
                                    <option value="37">ลำปาง</option>
                                    <option value="38">ลำพูน</option>
                                    <option value="39">สงขลา</option>
                                    <option value="40">สกลนคร</option>
                                    <option value="41">สมุทรปราการ</option>
                                    <option value="42">สมุทรสงคราม</option>
                                    <option value="43">สมุทรสาคร</option>
                                    <option value="44">สระแก้ว</option>
                                    <option value="45">สระบุรี</option>
                                    <option value="46">สุโขทัย</option>
                                    <option value="47">สุพรรณบุรี</option>
                                    <option value="48">อ่างทอง</option>
                                    <option value="49">อำนาจเจริญ</option>
                                    <option value="50">อุดรธานี</option>
                                    <option value="51">อุตรดิตถ์</option>
                                    <option value="52">อุทัยธานี</option>
                                    <option value="53">เชียงราย</option>
                                    <option value="54">เชียงใหม่</option>
                                    <option value="55">นครสวรรค์</option>
                                    <option value="56">บึงกาฬ</option>
                                    <option value="57">มุกดาหาร</option>
                                    <option value="58">ยโสธร</option>
                                    <option value="59">อุบลราชธานี</option>
                                    <option value="60">ศรีสะเกษ</option>
                                    <option value="61">หนองคาย</option>
                                    <option value="62">หนองบัวลำภู</option>
                                    <option value="63">เลย</option>
                                    
                                    <!-- More options... -->
                                </select>
                                <div class="invalid-feedback">กรุณาเลือกจังหวัด</div>
                            </div>

                            <div class="col-md-4">
                                <label for="senderDistrict" class="form-label">อำเภอ</label>
                                <select class="form-select" id="senderDistrict" required>
                                    <option selected disabled>เลือกอำเภอ</option>
                                    <option value="1">พระนคร</option>
                                    <option value="2">ดุสิต</option>
                                    <option value="3">หนองจอก</option>
                                    <option value="4">บางรัก</option>
                                    <option value="5">บางเขน</option>
                                    <option value="6">บางกอกน้อย</option>
                                    <option value="7">บางกอกใหญ่</option>
                                    <option value="8">ธนบุรี</option>
                                    <option value="9">ห้วยขวาง</option>
                                    <option value="10">คลองสามวา</option>
                                    <option value="11">ลาดกระบัง</option>
                                    <option value="12">ประเวศ</option>
                                    <option value="13">สวนหลวง</option>
                                    <option value="14">จตุจักร</option>
                                    <option value="15">บางซื่อ</option>
                                    <option value="16">พญาไท</option>
                                    <option value="17">ราชเทวี</option>
                                    <option value="18">คลองเตย</option>
                                    <option value="19">วัฒนา</option>
                                    <option value="20">บางนา</option>
                                    <option value="21">พระโขนง</option>
                                    <option value="22">ทุ่งครุ</option>
                                    <option value="23">บางบอน</option>
                                    <option value="24">หนองแขม</option>
                                    <option value="25">ลาดพร้าว</option>
                                    <option value="26">วังทองหลาง</option>
                                    <option value="27">บางแค</option>
                                    <option value="28">ทวีวัฒนา</option>
                                    <option value="29">คลองสาน</option>
                                    <option value="30">จอมทอง</option>
                                    <option value="31">บางขุนเทียน</option>
                                    <!-- More options... -->
                                </select>
                                <div class="invalid-feedback">กรุณาเลือกอำเภอ</div>
                            </div>

                            <div class="col-md-4">
                                <label for="senderSubdistrict" class="form-label">ตำบล</label>
                                <select class="form-select" id="senderSubdistrict" required>
                                    <option selected disabled>เลือกตำบล</option>
                                    <option value="1">พระนคร</option>
                                    <option value="2">ดุสิต</option>
                                    <option value="3">หนองจอก</option>
                                    <option value="4">บางรัก</option>
                                    <option value="5">บางเขน</option>
                                    <option value="6">บางกอกน้อย</option>
                                    <option value="7">บางกอกใหญ่</option>
                                    <option value="8">ธนบุรี</option>
                                    <option value="9">ห้วยขวาง</option>
                                    <option value="10">คลองสามวา</option>
                                    <option value="11">ลาดกระบัง</option>
                                    <option value="12">ประเวศ</option>
                                    <option value="13">สวนหลวง</option>
                                    <option value="14">จตุจักร</option>
                                    <option value="15">บางซื่อ</option>
                                    <option value="16">พญาไท</option>
                                    <option value="17">ราชเทวี</option>
                                    <option value="18">คลองเตย</option>
                                    <option value="19">วัฒนา</option>
                                    <option value="20">บางนา</option>
                                    <option value="21">พระโขนง</option>
                                    <option value="22">ทุ่งครุ</option>
                                    <option value="23">บางบอน</option>
                                    <option value="24">หนองแขม</option>
                                    <option value="25">ลาดพร้าว</option>
                                    <option value="26">วังทองหลาง</option>
                                    <option value="27">บางแค</option>
                                    <option value="28">ทวีวัฒนา</option>
                                    <option value="29">คลองสาน</option>
                                    <option value="30">จอมทอง</option>
                                    <option value="31">บางขุนเทียน</option>
                                        
                                       
                                    </optgroup>
                                </select>
                                <div class="invalid-feedback">กรุณาเลือกตำบล</div>
                            </div>

                            <div class="col-md-4">
                                <label for="senderAddress" class="form-label">บ้านเลขที่</label>
                                <input type="text" class="form-control" id="senderAddress" placeholder="บ้านเลขที่" required>
                                <div class="invalid-feedback">กรุณากรอกบ้านเลขที่</div>
                            </div>

                            <div class="col-md-4">
                                <label for="senderPostalCode" class="form-label">รหัสไปรษณีย์</label>
                                <input type="text" class="form-control" id="senderPostalCode" required>
                                <div class="invalid-feedback">กรุณากรอกรหัสไปรษณีย์</div>
                            </div>

                            <div class="col-md-4">
                                <label for="senderBirthday" class="form-label">วันที่</label>
                                <input type="date" id="senderBirthday" name="senderBirthday" class="form-control" required>
                                <div class="invalid-feedback">กรุณากรอกวันที่</div>
                            </div>

                            <h4 class="mt-4">ข้อมูลผู้รับ</h4>
                            <div class="col-md-4">
                                <label for="recipientName" class="form-label">ชื่อผู้รับ</label>
                                <input type="text" class="form-control" id="recipientName" required>
                                <div class="valid-feedback">Looks good!</div>
                            </div>

                            <div class="col-md-4">
                                <label for="recipientProvince" class="form-label">จังหวัด</label>
                                <select class="form-select" id="recipientProvince" required>
                                    <option selected disabled>เลือกจังหวัด</option>
                                    <option value="1">กรุงเทพมหานคร</option>
                                    <option value="2">กระบี่</option>
                                    <option value="3">กาญจนบุรี</option>
                                    <option value="4">กาฬสินธุ์</option>
                                    <option value="5">กำแพงเพชร</option>
                                    <option value="6">ขอนแก่น</option>
                                    <option value="7">จันทบุรี</option>
                                    <option value="8">ฉะเชิงเทรา</option>
                                    <option value="9">ชลบุรี</option>
                                    <option value="10">ชัยนาท</option>
                                    <option value="11">ชัยภูมิ</option>
                                    <option value="12">ชุมพร</option>
                                    <option value="13">ตรัง</option>
                                    <option value="14">ตราด</option>
                                    <option value="15">ตาก</option>
                                    <option value="16">นครนายก</option>
                                    <option value="17">นครปฐม</option>
                                    <option value="18">นครราชสีมา</option>
                                    <option value="19">นครศรีธรรมราช</option>
                                    <option value="20">นนทบุรี</option>
                                    <option value="21">นราธิวาส</option>
                                    <option value="22">น่าน</option>
                                    <option value="23">บุรีรัมย์</option>
                                    <option value="24">ปทุมธานี</option>
                                    <option value="25">ประจวบคีรีขันธ์</option>
                                    <option value="26">ปราจีนบุรี</option>
                                    <option value="27">ปัตตานี</option>
                                    <option value="28">พะเยา</option>
                                    <option value="29">เพชรบุรี</option>
                                    <option value="30">เพชรบูรณ์</option>
                                    <option value="31">แพร่</option>
                                    <option value="32">พังงา</option>
                                    <option value="33">ระนอง</option>
                                    <option value="34">ระยอง</option>
                                    <option value="35">ร้อยเอ็ด</option>
                                    <option value="36">ลพบุรี</option>
                                    <option value="37">ลำปาง</option>
                                    <option value="38">ลำพูน</option>
                                    <option value="39">สงขลา</option>
                                    <option value="40">สกลนคร</option>
                                    <option value="41">สมุทรปราการ</option>
                                    <option value="42">สมุทรสงคราม</option>
                                    <option value="43">สมุทรสาคร</option>
                                    <option value="44">สระแก้ว</option>
                                    <option value="45">สระบุรี</option>
                                    <option value="46">สุโขทัย</option>
                                    <option value="47">สุพรรณบุรี</option>
                                    <option value="48">อ่างทอง</option>
                                    <option value="49">อำนาจเจริญ</option>
                                    <option value="50">อุดรธานี</option>
                                    <option value="51">อุตรดิตถ์</option>
                                    <option value="52">อุทัยธานี</option>
                                    <option value="53">เชียงราย</option>
                                    <option value="54">เชียงใหม่</option>
                                    <option value="55">นครสวรรค์</option>
                                    <option value="56">บึงกาฬ</option>
                                    <option value="57">มุกดาหาร</option>
                                    <option value="58">ยโสธร</option>
                                    <option value="59">อุบลราชธานี</option>
                                    <option value="60">ศรีสะเกษ</option>
                                    <option value="61">หนองคาย</option>
                                    <option value="62">หนองบัวลำภู</option>
                                    <option value="63">เลย</option>
                                    
                                </select>
                                <div class="invalid-feedback">กรุณาเลือกจังหวัด</div>
                            </div>

                            <div class="col-md-4">
                                <label for="recipientDistrict" class="form-label">อำเภอ</label>
                                <select class="form-select" id="recipientDistrict" required>
                                    <option selected disabled>เลือกอำเภอ</option>
                                    <option value="1">พระนคร</option>
                                    <option value="2">ดุสิต</option>
                                    <option value="3">หนองจอก</option>
                                    <option value="4">บางรัก</option>
                                    <option value="5">บางเขน</option>
                                    <option value="6">บางกอกน้อย</option>
                                    <option value="7">บางกอกใหญ่</option>
                                    <option value="8">ธนบุรี</option>
                                    <option value="9">ห้วยขวาง</option>
                                    <option value="10">คลองสามวา</option>
                                    <option value="11">ลาดกระบัง</option>
                                    <option value="12">ประเวศ</option>
                                    <option value="13">สวนหลวง</option>
                                    <option value="14">จตุจักร</option>
                                    <option value="15">บางซื่อ</option>
                                    <option value="16">พญาไท</option>
                                    <option value="17">ราชเทวี</option>
                                    <option value="18">คลองเตย</option>
                                    <option value="19">วัฒนา</option>
                                    <option value="20">บางนา</option>
                                    <option value="21">พระโขนง</option>
                                    <option value="22">ทุ่งครุ</option>
                                    <option value="23">บางบอน</option>
                                    <option value="24">หนองแขม</option>
                                    <option value="25">ลาดพร้าว</option>
                                    <option value="26">วังทองหลาง</option>
                                    <option value="27">บางแค</option>
                                    <option value="28">ทวีวัฒนา</option>
                                    <option value="29">คลองสาน</option>
                                    <option value="30">จอมทอง</option>
                                    <option value="31">บางขุนเทียน</option>
                                 
                                </select>
                                    <!-- More options... -->
                                </select>
                                <div class="invalid-feedback">กรุณาเลือกอำเภอ</div>
                            </div>

                            <div class="col-md-4">
                                <label for="recipientSubdistrict" class="form-label">ตำบล</label>
                                <select class="form-select" id="recipientSubdistrict" required>
                                    <option selected disabled>เลือกตำบล</option>
                                    <optgroup label="พระนคร">
                                        <option selected disabled>เลือกตำบล</option>
                                    <option value="1">พระนคร</option>
                                    <option value="2">ดุสิต</option>
                                    <option value="3">หนองจอก</option>
                                    <option value="4">บางรัก</option>
                                    <option value="5">บางเขน</option>
                                    <option value="6">บางกอกน้อย</option>
                                    <option value="7">บางกอกใหญ่</option>
                                    <option value="8">ธนบุรี</option>
                                    <option value="9">ห้วยขวาง</option>
                                    <option value="10">คลองสามวา</option>
                                    <option value="11">ลาดกระบัง</option>
                                    <option value="12">ประเวศ</option>
                                    <option value="13">สวนหลวง</option>
                                    <option value="14">จตุจักร</option>
                                    <option value="15">บางซื่อ</option>
                                    <option value="16">พญาไท</option>
                                    <option value="17">ราชเทวี</option>
                                    <option value="18">คลองเตย</option>
                                    <option value="19">วัฒนา</option>
                                    <option value="20">บางนา</option>
                                    <option value="21">พระโขนง</option>
                                    <option value="22">ทุ่งครุ</option>
                                    <option value="23">บางบอน</option>
                                    <option value="24">หนองแขม</option>
                                    <option value="25">ลาดพร้าว</option>
                                    <option value="26">วังทองหลาง</option>
                                    <option value="27">บางแค</option>
                                    <option value="28">ทวีวัฒนา</option>
                                    <option value="29">คลองสาน</option>
                                    <option value="30">จอมทอง</option>
                                    <option value="31">บางขุนเทียน</option>
                                        
                                    </optgroup>
                                </select>
                                <div class="invalid-feedback">กรุณาเลือกตำบล</div>
                            </div>

                            <div class="col-md-4">
                                <label for="recipientAddress" class="form-label">บ้านเลขที่</label>
                                <input type="text" class="form-control" id="recipientAddress" placeholder="บ้านเลขที่" required>
                                <div class="invalid-feedback">กรุณากรอกบ้านเลขที่</div>
                            </div>

                            <div class="col-md-4">
                                <label for="recipientPostalCode" class="form-label">รหัสไปรษณีย์</label>
                                <input type="text" class="form-control" id="recipientPostalCode" required>
                                <div class="invalid-feedback">กรุณากรอกรหัสไปรษณีย์</div>
                            </div>

                            <div class="col-md-4">
                                <label for="recipientBirthday" class="form-label">วันที่</label>
                                <input type="date" id="recipientBirthday" name="recipientBirthday" class="form-control" required>
                                <div class="invalid-feedback">กรุณากรอกวันที่</div>
                            </div>

                            <div class="col-12">
                                <button class="btn btn-primary" type="submit">Submit form</button>
                            </div>
                        </form>
                    </td>
                </tr>
            </table>
        </center>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-p5bE18Mm3w/5eJ2/xt5jlHkwLO0NUI6qZ5RgX7LVZVxdL8HCnKoF/MN1j69O4l7e" crossorigin="anonymous"></script>
    <script>
        // JavaScript validation
        (function () {
            'use strict'

            // Fetch all the forms we want to apply custom Bootstrap validation styles to
            var forms = document.querySelectorAll('.needs-validation')

            // Loop over them and prevent submission
            Array.prototype.slice.call(forms)
                .forEach(function (form) {
                    form.addEventListener('submit', function (event) {
                        if (!form.checkValidity()) {
                            event.preventDefault()
                            event.stopPropagation()
                        }
                        form.classList.add('was-validated')
                    }, false)
                })
        })()
    </script>
</body>
</html>
