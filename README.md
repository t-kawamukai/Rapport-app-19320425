# README

## Usersテーブル
| Column             | Type    | Options                   |
| ------------------ | ------- | ------------------------- |
| family_name        | string  | null: false               |
| fast_name          | string  | null: false               |
| email              | string  | null: false, unique: true |
| encrypted_password | string  | null: false               |
| authority_id       | integer | null: false               |
| birthday           | date    | null: false               |
| sex_id             | integer | null: false               |
| tell               | string  | null: false               |

### association

## topsテーブル

## roomsテーブル

## room_usersテーブル

## schedulesテーブル

## care_recordsテーブル

## care_roomsテーブル

## noticesテーブル

## diariesテーブル

## volunteer_recruitmentテーブル
