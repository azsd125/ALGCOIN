<!DOCTYPE html>
<html>
<الرأس>
    <العنوان></العنوان>
	<meta charset="utf-8" />
    <script src="Scripts/jquery-1.9.1.min.js"></script>
    <link href="Content/bootstrap.min.css" rel="stylesheet" />
    <script src="Scripts/isRockFx.js"></script>
    <النص>
        (دالة () {
            $('#ButtonCal').click(
                وظيفة () {
                    //الحصول على قرض أو قرض شخصي
                    var para = { 'الارتفاع': $('#txbHeight').val()، 'الوزن': $('#txbWeight').val() };
                    //واجهة برمجة تطبيقات 呼叫
                    ExecuteAPI('مثال'، 'BMI'، الفقرة،
			// قم بإنشاء وظيفة رد الاتصال لـ WebAPI
                        الدالة (النتيجة) {
                            تنبيه(النتيجة.البيانات)؛
                        }
                        );
                }
                );
        });
    </script>
</head>
<الجسم>
    <div class="row" style="margin:10px">
        <div class="col-md-12">
            <div class="form-group">
                تسلق الجبال:
                <input id="txbHeight" class="form-control" placeholder="請輸入身高" />
                الاسم:
                <input id="txbWeight" class="form-control" placeholder="請輸入體重" />
                <br />
                <button class="btn btn-primary" id="ButtonCal">المفتاح</button>
            </div>
        </div>
    </div>
</body>
</html>
