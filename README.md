# Student manager

## Cách bắt đầu phát triển dự án

1. Clone code from github

```command
    git clone <path>
```

2. Tạo môi trường ảo và sử dụng nó

```command
    pip -m venv venv
    venv\Scripts\activate
```

3. Cài đặt các gói cần thiết

```command
    pip install -r requirements.txt
```

4. Sao chép file `.env.example` sang file `.env` và điền giá trị của bạn vào

```command
    cp .env.example .env
```

## Cách sử lý tình huống

1. Trường hợp cần cài thêm 1 gói thì cần cập nhật lại file requirements.txt

```command
    pip freeze > requirements.txt
```


## Beautiful alert

```javascript
    cuteAlert({
        type: 'warning', // "error", "info", "question"
        title: 'this is title',
        message: 'message ne',
        buttonText: 'bt' // optional
    }).then((data)=>{
        console.log(data);
    });
```
